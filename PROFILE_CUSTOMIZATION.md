# GitHub Profile Customization Guide

## What Has Been Added

Your GitHub profile README now includes:

### ✅ Visual Banner
- **Header Banner**: Animated waving gradient banner at the top using [Capsule Render](https://github.com/kyechan99/capsule-render)
- **Footer Banner**: Matching footer banner for visual consistency
- **Customizable**: You can change colors, text, animation style, and more

### ✅ Tech Stack Icons
- **Languages Section**: JavaScript, Python, Java, HTML5, CSS3
- **Frameworks & Libraries**: React, Node.js, Express, Bootstrap
- **Tools & Technologies**: Git, GitHub, VS Code, MongoDB, MySQL, Docker
- **Visual Icons**: Using [Devicon](https://devicon.dev/) for high-quality technology icons

### ✅ Additional Professional Sections
- About Me section
- GitHub Statistics (stats, top languages, streak)
- Featured Projects placeholder
- Connect With Me badges
- Visitor counter

> **Note**: The README contains placeholder values (email, LinkedIn) that you should customize with your own information. See the customization section below.

## How to Customize

### Change the Banner Text
In README.md line 3, find the Capsule Render API URL and locate the `text=` parameter:
```markdown
text=Welcome%20to%20My%20Profile
```
Replace `Welcome%20to%20My%20Profile` with your desired text (use %20 for spaces)

### Add/Remove Technology Icons
1. Visit [Devicon](https://devicon.dev/) to find your technologies
2. Copy the icon URL format:
```html
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/TECHNOLOGY/TECHNOLOGY-original.svg" alt="NAME" width="50" height="50"/>
```
3. Replace `TECHNOLOGY` with the technology name (e.g., `typescript`, `angular`, `postgresql`)

### Update Personal Information
- **Email**: Line 83 - Replace `your.email@example.com` with your actual email
- **LinkedIn**: Line 86 - Replace `yourprofile` with your LinkedIn username
- **About Me**: Lines 19-23 - Update with your personal information and goals

### Change Color Theme
The current theme is `tokyonight`. You can change it by updating the `theme=` parameter in the GitHub Stats image URLs (lines 61-62 for stats cards, line 66 for streak stats) to:
- `dark`
- `radical`
- `merko`
- `gruvbox`
- `tokyonight`
- `onedark`
- `cobalt`
- `synthwave`
- `highcontrast`
- `dracula`

### Banner Customization Options
Visit [Capsule Render](https://github.com/kyechan99/capsule-render) for more options:
- `type`: waving, wave, egg, shark, slice, rect, soft, rounded, cylinder, transparent
- `color`: gradient, or any color code
- `height`: Banner height in pixels
- `animation`: fadeIn, scaleIn, blink, blinking, twinkling, etc.

## Example Customizations

### Add TypeScript Icon
```html
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" width="50" height="50"/>
```

### Add Go Icon
```html
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" alt="Go" width="50" height="50"/>
```

### Add PostgreSQL Icon
```html
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="50" height="50"/>
```

## Resources

- **Devicon**: https://devicon.dev/ - Technology icons
- **Simple Icons**: https://simpleicons.org/ - More icons
- **Capsule Render**: https://github.com/kyechan99/capsule-render - Banner generator
- **GitHub Stats**: https://github.com/anuraghazra/github-readme-stats
- **Shields.io**: https://shields.io/ - Badge generator

## Tips

1. **Keep it Updated**: Update your tech stack as you learn new technologies
2. **Be Honest**: Only include technologies you actually know
3. **Add Projects**: Once you have projects, replace the "Coming soon" with actual project links
4. **Professional Photo**: Consider adding a profile picture on GitHub
5. **Bio**: Add a bio to your GitHub profile settings

---

*Created for Delta-44's GitHub profile*
