Nord Resume Theme for Grav

Nord Resume is a modern, privacy-focused adaptation of the classic Resume Theme. It has been re-engineered with the Nord color palette, automatic Dark/Light mode, and a local FontAwesome 7 icon system.

Features

❄️ Nord Color Palette: Uses the official Nord colors for a consistent, arctic look.

🌓 Auto Dark/Light Mode: Automatically detects system preferences (prefers-color-scheme).

🚀 FontAwesome 7: Upgraded icon system (v7.1.0) using local assets (GDPR compliant, no CDN).

🔧 Configurable: Admin Panel options for Gravatar, Footer text, and Credits.

📱 Fully Responsive: Built on the Foundation framework.

Classic Layouts: Preserves the Timeline, Skills, and Specialities layouts.

Installation

The easiest way to get started is to use the Skeleton package. Download it from the Skeleton Repository.

If you want to install only the theme into an existing Grav site:

Manual Installation

Clone this repository into your user/themes directory:

git clone [https://github.com/megvadulthangya/grav-theme-resume-nordic.git](https://github.com/megvadulthangya/grav-theme-resume-nordic.git) user/themes/resume-nordic


Enable the theme in your user/config/system.yaml:

pages:
  theme: resume-nordic


Note: This theme requires the Grav, Error, and Problems plugins.

Configuration

Nord Resume is configurable via the Grav Admin Panel. Go to Themes > Nord Resume to configure:

Gravatar: Enable/Disable, set Email, and adjust Size.

Footer: Custom copyright text.

Credits: Show/Hide "Powered by" text.

Dropdown: Enable/Disable menu dropdowns.

Alternatively, you can edit user/config/themes/resume-nordic.yaml.

Layouts & Content

To use the theme's special features, ensure your Markdown content follows these structures.

Specialities

File: pages/left/my-specialities/special.md

- icon: lightbulb
  text: Logo Design
  animation: fadeInDown


icon: Use modern FontAwesome 7 names (e.g., lightbulb, layer-group).

animation: Any Animate.css class.

Skills

File: pages/left/design-skills/skills.md

- name: Adobe Photoshop
  level: 8


level: 1-8 (Visual dots).

Experience (Work History)

File: pages/right/experience/experience.md

- date: 2018 - Present
  role: Senior Developer
  company: Tech Corp
  years: 5+
  description: "You can now use <b>HTML</b> tags here!"


Hobbies and Interests

File: pages/right/hobbies-and-interests/interests.md

- icon: camera-retro
  text: Photography
  animation: fadeIn
- icon: person-hiking
  text: Hiking


Credits

Original Theme by Fernando Báez & Grav Team.

Nord Adaptation by Gábor Gyöngyösi.

Color Palette by Arctic Ice Studio.
