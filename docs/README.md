# Personal Software Engineer Portfolio & Blog

Welcome to the source repository for my professional portfolio and technical blog, accessible globally at **[nguyen-huong.com](https://nguyen-huong.com)**. This site serves as a central hub to showcase my software engineering projects, system architectures, and technical writing.

---

## Tech Stack & Architecture

This website is engineered with a focus on maximum performance, security, and low-latency delivery:

*   **Frontend Structure:** Semantic HTML5 and modern CSS layouts optimized for scannability and responsive viewports.
*   **Design & Styling:** Utility-first components ensuring a consistent design system across all pages.
*   **Hosting & CDN:** Hosted on **Cloudflare Pages** utilizing edge network caching to deliver instant, global page loads with 100% uptime.
*   **Version Control & CI/CD:** Integrated with **GitHub Actions / Cloudflare Pipelines** for continuous deployment. Every commit to the `main` branch automatically builds and updates the live site within seconds.
*   **Privacy-First Analytics:** Engineered with locally hosted assets (including locally loaded font directories) to comply fully with European GDPR regulations.

---

## Repository Structure

The project follows a clean, decoupled architecture to separate content, legal frameworks, and global layouts:

```text
portfolio-website/
├── css/
│   └── styles.css        # One central stylesheet for your entire website
├── blogs/
│   ├── index.html        # Your Blog Feed page (nguyen-huong.com/blogs)
│   ├── clean-code.html   # Individual blog post article
│   └── edge-hosting.html # Individual blog post article
├── index.html            # The Core Hub (Hero, Skills, Projects, About, Contact)
├── privacy.html          # GDPR Privacy Policy
└── README.md             # Your professional repository documentation
