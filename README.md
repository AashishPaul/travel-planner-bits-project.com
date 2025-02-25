# travel-planner-bits-project.com
import type { Config } from "tailwindcss";
import type { Config } from "tailwindcss";
export default {
export default {
  darkMode: ["class"],
  darkMode: ["class"],
  content: [
  content: [
    "./pages/**/*.{ts,tsx}",
    "./pages/**/*.{ts,tsx}",
    "./components/**/*.{ts,tsx}",
    "./components/**/*.{ts,tsx}",
    "./app/**/*.{ts,tsx}",
    "./app/**/*.{ts,tsx}",
    "./src/**/*.{ts,tsx}",
    "./src/**/*.{ts,tsx}",
  ],
  ],
  prefix: "",
  prefix: "",
  theme: {
  theme: {
    container: {
    container: {
      center: true,
      center: true,
      padding: 
'
2rem
'
,
      padding: 
"
2rem
"
,
      screens: {
      screens: {
        
'
2xl
'
: 
'
1400px
'
        
"
2xl
"
: 
"
1400px
",
      }
      }
,
    },
    },
    extend: {
    extend: {
      colors: {
      colors: {
        border: 
'
hsl(var(--border))
'
,
        border: 
"
hsl(var(--border))
"
,
        input: 
'
hsl(var(--input))
'
,
        input: 
"
hsl(var(--input))
"
,
        ring: 
'
hsl(var(--ring))
'
,
        ring: 
"
hsl(var(--ring))
"
,
        background: 
'
hsl(var(--background))
'
,
        background: 
"
hsl(var(--background))
"
,
        foreground: 
'
hsl(var(--foreground))
'
,
        foreground: 
"
hsl(var(--foreground))
"
,
        primary: {
        primary: {
          DEFAULT: 
'
hsl(var(--primary))
'
,
          DEFAULT: 
"
hsl(var(--primary))
"
,
          foreground: 
'
hsl(var(--primary-foreground))
'
          foreground: 
"
hsl(var(--primary-foreground))
",
        },
        },
        secondary: {
        secondary: {
          DEFAULT: 
'
hsl(var(--secondary))
'
,
          DEFAULT: 
"
hsl(var(--secondary))
"
,
          foreground: 
'
hsl(var(--secondary-foreground))
'
          foreground: 
"
hsl(var(--secondary-foreground))
",
        },
        },
        destructive: {
        destructive: {
          DEFAULT: 
'
hsl(var(--destructive))
'
,
          DEFAULT: 
"
hsl(var(--destructive))
"
,
          foreground: 
'
hsl(var(--destructive-foreground))
'
          foreground: 
"
hsl(var(--destructive-foreground))
",
        },
        },
        muted: {
        muted: {
          DEFAULT: 
'
hsl(var(--muted))
'
,
          DEFAULT: 
"
hsl(var(--muted))
"
,
          foreground: 
'
hsl(var(--muted-foreground))
'
          foreground: 
"
hsl(var(--muted-foreground))
",
        },
        },
        accent: {
        accent: {
          DEFAULT: 
'
hsl(var(--accent))
'
,
          DEFAULT: 
"
hsl(var(--accent))
"
,
          foreground: 
'
hsl(var(--accent-foreground))
'
          foreground: 
"
hsl(var(--accent-foreground))
",
        },
        },
        popover: {
        popover: {
          DEFAULT: 
'
hsl(var(--popover))
'
,
          DEFAULT: 
"
hsl(var(--popover))
"
,
          foreground: 
'
hsl(var(--popover-foreground))
'
          foreground: 
"
hsl(var(--popover-foreground))
",
        },
        },
        card: {
        card: {
          DEFAULT: 
'
hsl(var(--card))
'
,
          DEFAULT: 
"
hsl(var(--card))
"
,
          foreground: 
'
hsl(var(--card-foreground))
'
          foreground: 
"
hsl(var(--card-foreground))
",
        },
        },
        
sidebar
: {
        
soft
: {
          DEFAULT: 
'hsl(var(--sidebar-background))'
,
          DEFAULT: 
"#F8FAFC"
,
          foreground: 
'hsl(var(--sidebar-foreground))'
,
          foreground: 
"#64748B"
,
        
primary: 'hsl(var(--sidebar-primary))'
,
        
}
,
      
'primary-foreground': 'hsl(var(--sidebar-primary-foreground))'
,
      
}
,
      
accent
: 
'hsl(var(--sidebar-accent))',
      
keyframes
: 
{
        
'accent
-
foreground'
: 
'hsl(var(--sidebar-accent-foreground))',
        
"accordion
-
down"
: 
{
          
border
: 
'hsl(var(--sidebar-border))'
,
          
from
: 
{ height: "0" }
,
          
ring
: 
'hsl(
var(--
sidebar
-
ring
)
)'
          
to
: 
{ height: "
var(--
radix
-
accordion-content-height
)
" },
        }
        }
,
        
},
        
"accordion-up": {
          
borderRadius
: {
          
from
: {
 height: "var(--radix-accordion-content-height)" },
          
lg
: 
'var(--radius)'
,
          
to
: 
{ height: "0" }
,
        
md: 'calc(var(--radius) - 2px)'
,
        
}
,
        
sm
: 
'calc(var(--radius) - 4px)'
        
fadeIn
: 
{
          
},
          
"0%": { opacity: "0", transform: "translateY(10px)" 
},
          
keyframes
: {
          
"100%"
: {
 opacity: "1", transform: "translateY(0)" },
        
'accordion-down': {
        
},
        
from
: {
        
slideIn
: {
          
height
: 
'0'
          
"0%"
: 
{ transform: "translateX(-100%)" },
          
},
          
"100%": { transform: "translateX(0)" 
},
        
to: {
        
},
      
height: 'var(--radix-accordion-content-height)'
      
},
      
}
      
animation: {
        
}
,
        
"accordion-down": "accordion-down 0.2s ease-out"
,
        
'
accordion-up
'
: 
{
        
"
accordion-up
"
: 
"accordion-up 0.2s ease-out",
        
from
: 
{
        
fadeIn
: 
"fadeIn 0.5s ease-out",
        
height
: 
'var(--radix
-
accordion-content-height)'
        
slideIn
: 
"slideIn 0.5s ease
-
out",
      },
      },
    
to: {
    
},
  
height: '0'
  
},
  
}
  
plugins: [require("tailwindcss-animate")],
				}
			},
			animation: {
				'accordion-down': 'accordion-down 0.2s ease-out',
				'accordion-up': 'accordion-up 0.2s ease-out'
			}
		}
	},
	plugins: [require("tailwindcss-animate")],
} satisfies Config;
} satisfies Config;
src/index.css
@tailwind base;
@tailwind base;
@tailwind components;
@tailwind components;
@tailwind utilities;
@tailwind utilities;
Expand 2 lines ...			
  :root {
  :root {
    --background: 0 0% 100%;
    --background: 0 0% 100%;
    --foreground: 222.2 84% 4.9%;
    --foreground: 222.2 84% 4.9%;
 
    --card: 0 0% 100%;
    --card: 0 0% 100%;
    --card-foreground: 222.2 84% 4.9%;
    --card-foreground: 222.2 84% 4.9%;
 
    --popover: 0 0% 100%;
    --popover: 0 0% 100%;
    --popover-foreground: 222.2 84% 4.9%;
    --popover-foreground: 222.2 84% 4.9%;
    --primary: 221.2 83.2% 53.3%;
    --primary: 222.2 47.4% 11.2%;
    --primary-foreground: 210 40% 98%;
    --primary-foreground: 210 40% 98%;
 
    --secondary: 210 40% 96.1%;
    --secondary: 210 40% 96.1%;
    --secondary-foreground: 222.2 47.4% 11.2%;
    --secondary-foreground: 222.2 47.4% 11.2%;
 
    --muted: 210 40% 96.1%;
    --muted: 210 40% 96.1%;
    --muted-foreground: 215.4 16.3% 46.9%;
    --muted-foreground: 215.4 16.3% 46.9%;
 
    --accent: 210 40% 96.1%;
    --accent: 210 40% 96.1%;
    --accent-foreground: 222.2 47.4% 11.2%;
    --accent-foreground: 222.2 47.4% 11.2%;
 
    --destructive: 0 84.2% 60.2%;
    --destructive: 0 84.2% 60.2%;
    --destructive-foreground: 210 40% 98%;
    --destructive-foreground: 210 40% 98%;
 
    --border: 214.3 31.8% 91.4%;
    --border: 214.3 31.8% 91.4%;
    --input: 214.3 31.8% 91.4%;
    --input: 214.3 31.8% 91.4%;
    --ring: 
222
.2 
84
% 
4
.
9
%;
    --ring: 
221
.2 
83.2
% 
53
.
3
%;
    --radius: 0.75rem;
  }
 
  * {
    @apply border-border;
  }
  
--radius:
 
0.5rem;
  
body
 
{
    @apply bg-background text-foreground antialiased;
    --sidebar-background: 0 0% 98%;
 
    --sidebar-foreground: 240 5.3% 26.1%;
 
    --sidebar-primary: 240 5.9% 10%;
 
    --sidebar-primary-foreground: 0 0% 98%;
 
    --sidebar-accent: 240 4.8% 95.9%;
 
    --sidebar-accent-foreground: 240 5.9% 10%;
 
    --sidebar-border: 220 13% 91%;
 
    --sidebar-ring: 217.2 91.2% 59.8%;
  }
  }
}
  
.
dark
 {
.
glass-card
 {
  
--background:
 
222.2
 
84%
 
4.9%;
  
@apply
 
bg-white/70
 
backdrop-blur-md
 
border border-white/20 shadow-lg;
    --foreground: 210 40% 98%;
}
    --card: 222
.
2
 
84% 4.9%;
.
animate-in
 
{
  
--card-foreground
: 
210
 
40%
 
98%;
  
animation
: 
fadeIn
 
0.5s
 
ease-out;
 
    --popover: 222.2 84% 4.9%;
    --popover-foreground: 210 40% 98%;
 
    --primary: 210 40% 98%;
    --primary-foreground: 222.2 47.4% 11.2%;
 
    --secondary: 217.2 32.6% 17.5%;
    --secondary-foreground: 210 40% 98%;
 
    --muted: 217.2 32.6% 17.5%;
    --muted-foreground: 215 20.2% 65.1%;
 
    --accent: 217.2 32.6% 17.5%;
    --accent-foreground: 210 40% 98%;
 
    --destructive: 0 62.8% 30.6%;
    --destructive-foreground: 210 40% 98%;
 
    --border: 217.2 32.6% 17.5%;
    --input: 217.2 32.6% 17.5%;
    --ring: 212.7 26.8% 83.9%;
    --sidebar-background: 240 5.9% 10%;
    --sidebar-foreground: 240 4.8% 95.9%;
    --sidebar-primary: 224.3 76.3% 48%;
    --sidebar-primary-foreground: 0 0% 100%;
    --sidebar-accent: 240 3.7% 15.9%;
    --sidebar-accent-foreground: 240 4.8% 95.9%;
    --sidebar-border: 240 3.7% 15.9%;
    --sidebar-ring: 217.2 91.2% 59.8%;
  }
}
}
@
layer
 
base
 {
@
keyframes
 
fadeIn
 {
  
*
 {
  
from
 {
    
@apply
 
border-border
;
    
opacity:
 
0
;
    transform: translateY(10px);
  }
  }
  to {
    
body
 
{
    
opacity:
 
1;
    
@apply
 
bg-background text-foreground
;
    
transform:
 
translateY(0)
;
  }
  }
}
}
src/pages/Index.tsx
// Update this page (the content is just a fallback if you fail to update the page)
import { useState } from "react";
import { Card } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Input } from "@/components/ui/input";
import { Calendar } from "@/components/ui/calendar";
import { Popover, PopoverContent, PopoverTrigger } from "@/components/ui/popover";
import { format } from "date-fns";
import { Calendar as CalendarIcon, MapPin, Plus } from "lucide-react";
interface Trip {
  id: string;
  destination: string;
  date: Date;
  notes: string;
}
const Index = () => {
const Index = () => {
  const [trips, setTrips] = useState<Trip[]>([]);
  const [date, setDate] = useState<Date>();
  const [destination, setDestination] = useState("");
  const [notes, setNotes] = useState("");
  const handleAddTrip = () => {
    if (!destination || !date) return;
    
    const newTrip: Trip = {
      id: Math.random().toString(36).substring(7),
      destination,
      date,
      notes,
    };
    
    setTrips([...trips, newTrip]);
    setDestination("");
    setDate(undefined);
    setNotes("");
  };
  return (
  return (
    <div className="min-h-screen 
flex
 
items
-
center
 
justify
-
center
 
bg
-
gray
-
100
">
    <div className="min-h-screen 
bg-gradient-to-b
 
from
-
soft
 
to
-
white
 
px
-
4 py
-
8
">
      <div className="
text
-
center
">
      <div className="
max
-
w-6xl mx-auto space-y-8 animate-in
">
        <
h1
 className="text-
4xl
 
font
-
bold mb
-4">
Welcome to Your Blank App</h1>
        <
div
 className="text-
center
 
space
-
y
-4">
          <
p
 className="text-
xl
 
text
-
gray
-
600
">
Start
 
building your amazing project here!</p
>
          <
h1
 className="text-
4xl
 
font
-
bold tracking
-
tight
">
Travel
 
Planner</h1
>
          <p className="text-soft-foreground max-w-2xl mx-auto">
            Plan your next adventure with our intuitive travel planner. Add destinations,
            dates, and notes to keep track of your upcoming trips.
          </p>
        </div>
        <Card className="glass-card p-6 max-w-2xl mx-auto">
          <div className="space-y-4">
            <div className="flex gap-4">
              <div className="flex-1">
                <div className="relative">
                  <MapPin className="absolute left-3 top-3 h-5 w-5 text-soft-foreground" />
                  <Input
                    placeholder="Enter destination"
                    value={destination}
                    onChange={(e) => setDestination(e.target.value)}
                    className="pl-10"
                  />
                </div>
              </div>
              <Popover>
                <PopoverTrigger asChild>
                  <Button variant="outline" className="w-[220px] justify-start text-left font-normal">
                    <CalendarIcon className="mr-2 h-4 w-4" />
                    {date ? format(date, "PPP") : "Pick a date"}
                  </Button>
                </PopoverTrigger>
                <PopoverContent className="w-auto p-0" align="start">
                  <Calendar
                    mode="single"
                    selected={date}
                    onSelect={setDate}
                    initialFocus
                  />
                </PopoverContent>
              </Popover>
            </div>
            <Input
              placeholder="Add notes about your trip"
              value={notes}
              onChange={(e) => setNotes(e.target.value)}
              className="min-h-[80px]"
            />
            <Button onClick={handleAddTrip} className="w-full">
              <Plus className="mr-2 h-4 w-4" /> Add Trip
            </Button>
          </div>
        </Card>
        <div className="grid gap-4 md:grid-cols-2 lg:grid-cols-3">
          {trips.map((trip) => (
            <Card key={trip.id} className="glass-card p-6 animate-fadeIn">
              <div className="space-y-2">
                <div className="flex items-start justify-between">
                  <h3 className="font-semibold">{trip.destination}</h3>
                  <span className="text-sm text-soft-foreground">
                    {format(trip.date, "MMM d, yyyy")}
                  </span>
                </div>
                {trip.notes && (
                  <p className="text-sm text-soft-foreground">{trip.notes}</p>
                )}
              </div>
            </Card>
          ))}
        </div>
      </div>
      </div>
    </div>
    </div>
  );
  );
