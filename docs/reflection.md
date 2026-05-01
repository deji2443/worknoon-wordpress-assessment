System Architecture Overview
WordPress CMS
Page builder (Elementor)
Caching layer (WP Rocket)
Analytics integration (Google Analytics)
Hosting environment


Key Decisions
Used Elementor for rapid UI development
Optimized assets for performance
Structured schema for SEO


Tradeoffs
Elementor vs custom theme (speed vs flexibility)
Plugin usage vs custom code



Challenges
DNS/subdomain issues → resolved via proper A record + propagation
Page speed optimization → solved using caching + compression


Improvements
Convert to headless WordPress
Add CDN (Cloudflare)
Implement CI/CD pipeline