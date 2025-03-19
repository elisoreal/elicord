# Elicord Discord Theme

A cute, white and pink Discord theme with rounded corners and soft aesthetics.

## Features

- Clean white background for a fresh look
- Soft pink accent colors
- Extra rounded corners for a cute bubbly feel
- Pastel status indicators
- Improved spacing and animations
- & More!

## Installation

### Powercord/Vencord

Add this to your QuickCSS:

```/**
 * @name elicord
 * @description A cute, white and pink discord theme with rounded corners
 * @author elisoreal
 * @version 1.0.0
 * @website https://eli.is-a.dev
 * @source https://github.com/elisoreal/elicord/tree/main
*/

@import url('https://refact0r.github.io/midnight-discord/midnight.css');

:root {
	--font: 'Quicksand';
	--corner-text: 'elicord :3';
	--divider-thickness: 2px;

	--online-indicator: #a5d6a7;
	--dnd-indicator: #ffb3c1;
	--idle-indicator: #ffe0b2;
	--streaming-indicator: #d1c4e9;

	--accent-1: hsl(350, 100%, 88%);
	--accent-2: hsl(350, 100%, 83%);
	--accent-3: hsl(350, 100%, 83%);
	--accent-4: hsl(350, 100%, 78%);
	--accent-5: hsl(350, 100%, 73%);
	--mention: hsla(350, 100%, 88%, 0.2);
	--mention-hover: hsla(350, 100%, 88%, 0.3);

	--text-0: #ffffff;
	--text-1: #5e5e5e;
	--text-2: #444444;
	--text-3: #555555;
	--text-4: #777777;
	--text-5: #aaaaaa;

	--bg-1: #ffecf0;
	--bg-2: #fff4f6;
	--bg-3: #fffafa;
	--bg-4: #ffffff;
	--hover: hsla(350, 100%, 95%, 0.5);
	--active: hsla(350, 100%, 90%, 0.7);
	--message-hover: hsla(350, 100%, 95%, 0.5);

	--spacing: 14px;

	--list-item-transition: 0.3s ease;
	--unread-bar-transition: 0.3s ease;
	--moon-spin-transition: 0.5s ease;
	--icon-spin-transition: 1.2s ease;

	--roundness-xl: 24px;
	--roundness-l: 22px;
	--roundness-m: 18px;
	--roundness-s: 14px;
	--roundness-xs: 12px;
	--roundness-xxs: 10px;

	--discord-icon: none;
	--moon-icon: block;
	--moon-icon-url: url('https://cdn-icons-png.flaticon.com/512/616/616430.png');
	--moon-icon-size: 20px;

	--login-bg-filter: brightness(1.1) saturate(0.8);
	--green-to-accent-3-filter: hue-rotate(280deg) saturate(0.8);
	--blurple-to-accent-3-filter: hue-rotate(260deg) saturate(0.8);

	--windows-nav: none;
	--custom-nav: block;
}
```

## Credits

- Inspired by various Discord themes in the community

## License

MIT © [elisoreal]
