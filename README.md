# Proxy Server Cyberpunk Animation

An interactive, cyberpunk-themed visualization explaining how proxy servers work. This single HTML file creates an animated explanation of proxy server functionality with a sleek, neon-styled interface.

![Proxy Server Animation](https://github.com/DoingFedTime/Proxy-Explainer-HTML/raw/main/proxyserverexplained.gif)

## Features

- **Interactive Animation:** Visual representation of data flow between client, proxy server, and web server
- **Cyberpunk Styling:** Neon colors, grid background, and futuristic design elements
- **Educational Content:** Clear explanations of proxy server functionality and benefits
- **Self-Contained:** Single HTML file with no external dependencies
- **Responsive Design:** Works on both desktop and mobile devices

## Live Demo

View the live demo: [Proxy Server Animation](https://doingfedtime.com/proxy-server-explained/)

## Key Concepts Explained

The animation illustrates the following key concepts:

1. **Request Flow:** How client requests are routed through a proxy to reach the destination server
2. **IP Masking:** How proxy servers hide the client's real IP address
3. **Response Handling:** How responses travel back through the proxy to the client
4. **Core Benefits:**
   - Anonymity and privacy
   - Access control and content filtering
   - Performance improvements through caching
   - Geographic restriction bypass

## Usage

Simply open the HTML file in any modern web browser. No installation or dependencies required.

```bash
# Clone the repository
git clone https://github.com/DoingFedTime/Proxy-Explainer-HTML.git

# Navigate to the directory
cd proxy-animation

# Open the HTML file in your browser
open index.html  # on macOS
# or
start index.html  # on Windows
```

## Customization

The animation can be easily customized by modifying the CSS variables at the top of the stylesheet:

```css
:root {
    --neon-text-color: #f637ec;
    --neon-border-color: #08f7fe;
    --background-color: #0a0a16;
    --grid-color: rgba(8, 247, 254, 0.1);
    --accent-color: #fe53bb;
    --secondary-color: #09fbd3;
    --terminal-green: #39ff14;
}
```

## License

MIT License - See LICENSE file for details.

## Credits

Created by Sam Bent for educational purposes (first use in youtube.com/@sam_bent ).

---

Feel free to use this animation for educational content, presentations, or as a learning resource about network security and proxy servers.
