---
title: Intercom
description: A simple and performant YouTube component.
links:
  - label: Source
    icon: i-simple-icons-github
    to: https://github.com/nuxt/scripts-and-assets/blob/main/modules/nuxt-third-party-capital/src/runtime/components/YoutubeEmbed.ts
    size: xs
---

The `<YoutubeEmbed>` component can be used to display a YouTube embed.
It uses [lite-youtube-embed](https://github.com/paulirish/lite-youtube-embed) to load significantly faster.

## Minimal Example

```vue
<template>
  <div>
    <YoutubeEmbed
      video-id="d_IFKP1Ofq0"
      play-label="Play"
    />
  </div>
</template>
```

## Props

- `videoId`: The ID of the video
  - **type**: `string`
  - **required**
- `playLabel`: The label of the play button. This is for a11y purposes.
  - **type**: `string`
  - **required**
- `width`: Width of the player
  - **type**: `string`
- `height`: Height of the player
  - **type**: `string`
- `params`: [Parameters](https://developers.google.com/youtube/player_parameters#Parameters) for the player.