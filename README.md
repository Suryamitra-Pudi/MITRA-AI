<svg xmlns="http://www.w3.org/2000/svg" width="400" height="80" viewBox="0 0 400 80">
  <defs>
    <!-- Define the glow filter -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <style>
    text {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
      font-weight: bold;
      font-size: 32px;
      fill: #00ffcc; /* Neon Cyan text color */
      filter: url(#glow);
    }
    
    /* Support dark/light mode themes natively */
    @media (prefers-color-scheme: light) {
      text {
        fill: #ff0055; /* Neon Pink/Red for light backgrounds */
      }
    }
  </style>

  <text x="20" y="50">Hello GitHub!</text>
</svg>

