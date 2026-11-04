comming soon
<picture>
  <!-- Dark mode glowing text -->
  <source media="(prefers-color-scheme: dark)" srcset="data:image/svg+xml;utf8,<svg xmlns='http://w3.org' width='400' height='80'><defs><filter id='glow'><feGaussianBlur stdDeviation='3.5' result='coloredBlur'/><feMerge><feMergeNode in='coloredBlur'/><feMergeNode in='SourceGraphic'/></feMerge></filter></defs><style>text{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Helvetica,Arial,sans-serif;font-weight:bold;font-size:32px;fill:%2300ffcc;filter:url(%23glow);}</style><text x='10' y='50'>Hello GitHub!</text></svg>">
  
  <!-- Light mode glowing text (darker glow for contrast) -->
  <source media="(prefers-color-scheme: light)" srcset="data:image/svg+xml;utf8,<svg xmlns='http://w3.org' width='400' height='80'><defs><filter id='glowLight'><feGaussianBlur stdDeviation='2.5' result='blur'/><feMerge><feMergeNode in='blur'/><feMergeNode in='SourceGraphic'/></feMerge></filter></defs><style>text{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Helvetica,Arial,sans-serif;font-weight:bold;font-size:32px;fill:%23ff0055;filter:url(%23glowLight);}</style><text x='10' y='50'>Hello GitHub!</text></svg>">
  
  <!-- Fallback image -->
  <img src="data:image/svg+xml;utf8,<svg xmlns='http://w3.org' width='400' height='80'><text x='10' y='50' font-size='32' fill='%2300ffcc'>Hello GitHub!</text></svg>" alt="Glowing Text">
</picture>
