# Golf Slot Watch

ゴルフ場空き枠・安値・天気通知

## Repository

Recommended repository name: `golf-slot-watch`

## Domain candidates

First candidate: `golfslot.jp`

Other candidates:

- `golfslot.jp`
- `golfaki.jp`
- `golftimealert.jp`
- `golfyasui.jp`

## Concept

空き枠、安値、雨天キャンセル、天気、練習場を通知し、ゴルフ場予約と用品へ送客する。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 予約成果報酬
- 用品 affiliate
- 宿泊送客
- 練習場掲載
- コンペ広告

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
