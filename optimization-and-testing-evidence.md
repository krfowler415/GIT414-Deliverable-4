GIT 414
Kevin Fowler
Deliverable 4 - Optimization and Testing Evidence

Scope 
Implemented homepage preview. Sources, licenses, original dimensions, and individual optimized file sizes are recorded in the separate Asset Inventory doc.

Media Optimization and Art Direction
I resized and compressed the three featured animal images into multiple WebP and JPEG versions. I used picture, srcset, and sizes so browsers can load the appropriate images for potential users’ different screen sizes. The same animal compositions work across the layouts, although I did also crop the replacement Elf Owl photograph to fit better in the cards.
I also converted the hero background from PNG (approximately 3.3 MB) to WebP (192 KB) and created a separate ultrawide version for larger screens.

Accessibility and Typography
All three featured animal images have descriptive alt text attached. The hero background is just decorative so it doesn't require any alt text. I also included a skip link, labeled navigation, visible keyboard focus styles, and reduced-motion support for the mobile menu. The homepage doesn't use SVGs, audio, video, or embeds.
I used Figtree for the headings and Outfit for the body text. Arial and Helvetica are used as the fallback fonts. Both chosen fonts are available for use through Google Fonts under the SIL Open Font License 1.1. I used responsive heading sizes, appropriate line spacing, and limits on text width to help improve overall readability. The fonts also use display=swap and preconnect hints to help with loading.

Layout Stability and Testing
I set the dimensions for the animal images and hero section to help prevent the layout from shifting while the page loads.
Responsive widths: I manually resized the browser window between narrow and wide screen sizes to check how the website responded. The animal cards adjusted correctly between one, two, and three-column layouts as the available screen space changed.
200% zoom: I tested the browser zoom at 200% which caused the layout to adapt to the tablet-view layout; the page still remained fully visible and usable.
Slow 4G: I used Chrome DevTools with cache disabled; it recorded 12 requests, 387 KB transferred, and a 3.90-second finish time. All listed requests returned HTTP 200, including WebP images and web fonts.

AI Disclosure
Generative AI was used to create the decorative Sonoran Desert hero artwork. I wanted the artwork to reflect the website's color scheme, including the orange ocotillo flowers and pink prickly pear flowers so I tried to subtly add in my color scheme. Several visual options were considered and the eventual selected design was then reviewed at different widths. The image was also compressed to WebP. An ultrawide version was created and CSS positioning and hero height were adjusted to help improve the overall appearance.
