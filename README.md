# AI & Economics: The Ghost in the Machine
**Assignment 4: Tailwind CDN Single Page Application**

## Live Site
[View the Project Here](https://mohamedk1101.github.io/ai-economics-spa/)



## Design Philosophy
For this project, I chose the disciplinary field of **Economics**, specifically focusing on **Algorithmic Markets**. 

* **Theme:** "The Terminal" aesthetic, using a high-contrast Dark Mode to represent the technical nature of modern finance.
* **Narrative:** The layout follows a vertical scroll that transitions from market efficiency (The Miracle) to the lack of transparency (The Black Box).
* **Consistency:** I used a monospace font and a consistent color palette to ensure the page feels like a single, cohesive application.



## 20+ Creative Tailwind Styles Used
To meet the technical requirements, I utilized the following 20+ utility classes and techniques:

### **Layout & Responsiveness**
1.  `grid-cols-1 md:grid-cols-3`: Responsive grid that shifts from 1 column on mobile to 3 on desktop.
2.  `max-w-6xl`: Limits the width of the content for better readability.
3.  `mx-auto`: Centers the main containers on the screen.
4.  `flex flex-col md:flex-row`: Adjusts the "Risk" section layout based on screen size.

### **Animations & Motion**
5.  `animate-pulse`: Used on the background lines to simulate a "live" data stream.
6.  `animate-pulse-slow`: A custom-timed pulse created in the tailwind.config for visual variety.
7.  `transition-all`: Ensures smooth color and size changes during interactions.
8.  `duration-500`: Sets the speed of transitions to half a second for a "premium" feel.

### **Interactivity (Hover Effects)**
9.  `group-hover`: Allows child elements (like the underline) to animate when the parent card is hovered.
10. `hover:border-terminalGreen`: Changes the card border color on interaction.
11. `hover:shadow-[0_0_30px_rgba(16,185,129,0.2)]`: A custom glow effect using square-bracket notation.
12. `hover:bg-terminalGreen`: Used on the "Initialize System" button for a hover-state fill.

### **Typography & Branding**
13. `tracking-tighter`: Tightens letter spacing for a modern, aggressive financial headline.
14. `font-black`: The heaviest font weight for maximum impact on section titles.
15. `font-mono`: Used throughout to maintain the "coding terminal" look.
16. `selection:bg-terminalGreen`: Customizes the color of the background when text is highlighted by the user.

### **Visual Effects & Styling**
17. `backdrop-blur-sm`: Creates a "Glassmorphism" effect on the benefit cards.
18. `bg-slate-900/50`: Uses an opacity slash to make the card background semi-transparent.
19. `border-l-4`: Creates a thick vertical accent line for philosophical quotes.
20. `bg-red-950/10`: A very subtle red tint used to differentiate the "Risk" section from the "Benefit" section.
21. `z-10`: Manages layer stacking to ensure text stays above background animations.
22. `overflow-hidden`: Prevents animation elements from causing accidental horizontal scrolling.



## 🛠️ Technical Process
I built this SPA from scratch using the Tailwind Play CDN. I focused on clean alignment and a consistent padding strategy (`py-24`) to give the page a professional, spacious feel. Every color choice was intentional to reflect the "Economics" theme, using greens for growth and reds for systemic risk.
