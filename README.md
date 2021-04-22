# pulsing-notifications
[Absol's pulsing notifications](https://github.com/absxl/slate-snippets/blob/master/Pulsing%20notifications.css) but it works for Discord, not [Slate](https://github.com/DiscordStyles/Slate). All credit goes to [absol](https://github.com/absxl/slate-snippets/blob/master/Pulsing%20notifications.css) for the code.

```css
@keyframes pulse {
  from {
    transform: scale(1);
  }
  to {
    transform: scale(1.1);
  }
}

.unread-2lAfLh {
  visibility: hidden;
}

.modeUnread-1qO3K1 .name-23GUGE, .modeUnread-1qO3K1:hover .name-23GUGE, .notInteractive-1X92pj.modeConnected-3IsKId .name-23GUGE, .notInteractive-1X92pj.modeSelected-346R90 .name-23GUGE {
  animation: pulse 2s infinite alternate;
  padding-left: 5px;
}
```
