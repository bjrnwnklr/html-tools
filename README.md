# HTML Tools

A collection of single-page HTML utilities that combine HTML, JavaScript, and CSS to provide useful functionality—no server required, no build step needed.

## Inspiration

This project is inspired by [Simon Willison's html-tools collection](https://tools.simonwillison.net/), which demonstrates the power and simplicity of building lightweight, self-contained web applications. As Simon writes in his blog post [Useful patterns for building HTML tools](https://simonwillison.net/2025/Dec/10/html-tools/):

> "I've started using the term **HTML tools** to refer to HTML applications that I've been building which combine HTML, JavaScript, and CSS in a single file and use them to provide useful functionality. I have built over 150 of these in the past two years, almost all of them written by LLMs."

## Philosophy

These tools follow a few key principles:

1. **Single file** - Each tool is a standalone HTML file with inline CSS and JavaScript. No build process, no compilation, just open and use.

2. **No frameworks** - These tools avoid heavy frameworks like React. Instead, they use vanilla JavaScript and lightweight libraries loaded from CDNs when needed.

3. **Self-contained** - Everything works offline (except for tools that explicitly need external APIs). Copy the file, open it in a browser, and it works.

4. **LLM-friendly** - Built with assistance from AI coding tools, these applications are designed to be easily understood, modified, and extended by both humans and LLMs.

5. **Practical utility** - Each tool solves a real problem or makes a specific task easier.

## Tools

### [Countdown Timer](countdown-timer.html)
A clean, elegant countdown timer with:
- Preset buttons for 1, 3, and 5 minutes
- Custom time input (minutes and seconds)
- Circular progress visualization
- Dark mode optimized design
- Optional sound notification
- Background color change when time expires

## How to Use

1. **Online**: Visit the [live version](https://YOUR_USERNAME.github.io/html-tools/) (once deployed)

2. **Locally**: 
   - Clone this repository
   - Open any `.html` file in your browser
   - That's it!

3. **Customize**:
   - These tools are designed to be easily modified
   - Open the HTML file in any text editor
   - All code is visible and hackable
   - Use AI assistants like Claude or ChatGPT to help modify them

## Building Your Own Tools

If you want to create similar tools, here are some patterns that work well:

- **Persist state in the URL** - Use URL parameters to make tools shareable and bookmarkable
- **Use localStorage** - Store user preferences or API keys locally
- **Load from CDNs** - Use services like cdnjs or jsdelivr for any libraries you need
- **Keep them small** - A few hundred lines of code is ideal for maintainability
- **Avoid build steps** - Inline everything to keep it simple

## Contributing

Have a useful tool to add? Feel free to:
1. Fork this repository
2. Add your single-file HTML tool
3. Update this README with a description
4. Submit a pull request

## License

Copyright 2025 [Your Name]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Acknowledgments

Huge thanks to [Simon Willison](https://simonwillison.net/) for pioneering this approach and sharing his techniques. His work demonstrates that you don't need complex build systems or heavy frameworks to create genuinely useful web applications.

---

*Built with the help of Claude, because why not use the tools available to us?*
