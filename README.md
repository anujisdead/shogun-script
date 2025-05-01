# shogun-script

## 🎨 Design Guidelines (For AI / Cursor Use)

Please follow these UI/UX design principles when making visual or layout changes to this application:

1. **Use Tailwind CSS Only**
   - All styling should be done using [Tailwind CSS](https://tailwindcss.com/).
   - Do not introduce external CSS frameworks or write custom CSS unless absolutely necessary.

2. **Keep It Simple**
   - Avoid overly complex or unconventional UI elements.
   - Stick to clean, minimalist layouts with clear visual hierarchy.

3. **Color Palette**
   Use the following custom color palette consistently across the app:

   | Purpose            | Hex Code     |
   |--------------------|--------------|
   | Primary Base       | `#76827F`    |
   | Background Dark    | `#02040A`    |
   | Dark Gray          | `#0E1218`    |
   | Soft Black         | `#11161A`    |
   | Accent/Contrast    | `#03050B`    |
   | Brown              | `#774936`    |
   | Slate              | `#2A2D34`    |
   | Teal               | `#012A36`    |

   > Tip: Configure these in your `tailwind.config.js` file under `extend.colors` for easier use like `bg-primary`, `text-dark`, `bg-brown`, etc.

4. **Responsiveness**
   - Design must be responsive — use Tailwind's mobile-first utilities (`sm:`, `md:`, `lg:`, etc.).
   - Test for legibility and layout integrity on all screen sizes.

5. **Component Reuse**
   - Reuse existing components and UI patterns.
   - Maintain consistency in padding, margins, typography, and shadows.

---

These guidelines are intended to help maintain a consistent, scalable design system throughout the application while enabling AI-assisted development.
