# ScreenGrab.cloud

Take screengrabs of HTML elements or React components on your website

## Get Started

Fist log into https://screengrab.cloud and get your API Key from the dashboard

## Quick Start

```ts
import { ScreenGrab } from 'screngrab.cloud'

const screengrab = ScreenGrab('api-key')

const image = await screengrab.url('https://memezoo.app').grab()

console.log('screengrab url', image.url)

```

For detailed information refer to https://docs.screengrab.cloud 