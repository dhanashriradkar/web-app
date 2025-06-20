# web-app🎥 STRMLY Vertical Video Feed (Web)
A responsive vertical video feed web app built with React.js, inspired by platforms like YouTube Shorts, Reels, and TikTok. This app replicates the layout, video interactions, and overlay features as defined in the STRMLY Frontend Developer Technical Challenge.

🚀 Features
Vertical Video Feed: Videos scroll full-screen, one per viewport.

Auto Play/Pause: Videos auto-play when in view and pause when out of view.

Tap to Play/Pause & Mute/Unmute.

UI Overlays:

Video title, episode tag, and description (clamped to 3 lines).

Left overlay: Hashtags, creator name, and Follow button.

Right overlay: Like, Comment, Share, Earnings (Tip), and Menu icon.

Bottom Navigation Bar: Home, Shorts, Add, Search, and Profile (Dummy).

Mock Data Integration: Simulated API fetch with delays and error handling.

Loading State & Graceful Fallbacks.

Responsive Design: Works on mobile, tablet, and desktop screens.

Performance Optimization:

React.memo, useCallback, and useMemo.

Lazy loading and smooth scrolling.

🛠️ Tech Stack
React.js with Functional Components

Tailwind CSS for Styling

HTML5 Video Element

Mock API Simulation (using JSON data and setTimeout())

