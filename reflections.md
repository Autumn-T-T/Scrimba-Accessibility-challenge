# Accessibility Reflections

## 1. What accessibility enhancements were the most challenging to implement, and why?

Honestly, the hardest part was getting **labels on all the form inputs** and figuring out the **alt text for images**.  

- For the labels, it was tricky to make sure each input actually had one that made sense, without breaking the layout. I realized that placeholders alone aren’t enough for accessibility, so I had to actually add visible labels, which was kind of a small headache.  
- For images, I had to think about whether they were just decorative or actually important for understanding the page. Some of them were hard to describe in a single sentence that actually made sense for screen readers.

---

## 2. How do ARIA attributes improve the experience for users relying on assistive technologies?

ARIA attributes basically give extra hints to screen readers and other assistive tech about what’s going on on the page.  

- They can tell a screen reader that something is a button, a menu, or if something opened or closed.  
- They’re especially useful when the visible labels or text aren’t enough to explain what an element does.  

Using ARIA makes the page way more understandable for people who rely on assistive tech, so they don’t get lost or confused.

---

## 3. What tools did you use to check color contrast, and how did they help?

I used a couple of tools (and my own experience) to make sure the text actually stood out enough from the background:  

- **WebAIM Contrast Checker** – I put in my text and background colors to see if they passed the WCAG AA standard (at least 4.5:1 for normal text). Though honestly I feel considering my years in graphic design and digital art in general it was pretty easy to just keep in mind what looks good/ easy to read/use when going into account of what wanting your consumers to know what they're looking at or listening to with a screen reader!
- **Chrome Lighthouse** – ran an audit on the page and it flagged any low-contrast text automatically.  

These tools were super helpful because they made it obvious when something was too light or hard to read. Honestly, I probably would’ve missed some of those contrast issues without them.
