## Hi, I'm Sushanth.

Software engineer at **Google** by day. **15 production iOS apps** shipped independently on the side.

The portfolio is mostly consumer subscription apps built on the Anthropic API + Apple's on-device stack (StoreKit 2, ActivityKit, WidgetKit, AVAudioEngine, WhisperKit). A few of them:

- **[ScribeAI](https://apps.apple.com/us/app/scribe-ai/id6755475602)** — voice-to-note transcription with AI summarization
- **[MeetingMind](https://apps.apple.com/us/app/meetingmind-ai-note-taker/id6757317991)** — real-time meeting transcription, action items, follow-up drafts
- **[Audexa](https://apps.apple.com/us/app/audexa/id6756477258)** — live AI radio, on-device generation
- **[ReadAloud AI](https://apps.apple.com/us/app/readaloudai-voice-reader/id6757346255)** — neural TTS with custom voice cloning
- **[ClearVoice Recorder](https://apps.apple.com/us/app/clearvoice-recorder/id6758923895)** — voice memo + ASR + summary
- **Lullaby Haven** — generated bedtime stories for kids *(in App Store review)*
- … 9 others across utility, productivity, finance, and games

### Libraries

- **PaywallKit** — server-controlled paywall templates with A/B testing; in production across 7 of the apps above
- **RatingKit** — App Store rating prompt that respects Apple's review-prompt guidelines and tracks user satisfaction before asking

### Recent open-source contributions

Shipping fixes and small features across iOS, AI/agent infrastructure, runtimes, and dev tooling — repos I use in production.

**Merged**

| Repo | PR | Scope |
| --- | --- | --- |
| [pnpm/pnpm](https://github.com/pnpm/pnpm/pull/12393) | #12393 | Interactive checkbox summary line in `update -i` / `audit --fix -i` |
| [pnpm/pnpm](https://github.com/pnpm/pnpm/pull/12380) | #12380 | `selectProjectByDir` Windows path normalization |
| [better-auth/better-auth](https://github.com/better-auth/better-auth/pull/10048) | #10048 | Drizzle generator array `defaultValue` serialization |
| [TanStack/router](https://github.com/TanStack/router/pull/7617) | #7617 | Drop broken nav entry |
| [ml-explore/mlx-swift](https://github.com/ml-explore/mlx-swift/pull/422) | #422 | Resolve default device from MLX core |
| [DataDog/datadog-ci](https://github.com/DataDog/datadog-ci/pull/2347) | #2347 | `jsonOutput` for internal logger |
| [airbnb/lottie-ios](https://github.com/airbnb/lottie-ios/pull/2688) | #2688 | Recognize the IANA `.lot` extension |
| [kean/Pulse](https://github.com/kean/Pulse/pull/371) | #371 | Opaque graphics context on icon resize |
| [exyte/Chat](https://github.com/exyte/Chat/pull/282) | #282 | Dynamic-Type-scalable username |
| [ml-explore/mlx-swift-examples](https://github.com/ml-explore/mlx-swift-examples/pull/481) | #481 | `image-tool` README |

**In review** — selected open PRs at hiring-relevant repos

| Repo | PR | Scope |
| --- | --- | --- |
| [solidjs/solid](https://github.com/solidjs/solid/pull/2785) | #2785 | `action()` awaits non-Promise thenables |
| [solidjs/solid](https://github.com/solidjs/solid/pull/2784) | #2784 | `<Repeat>` empty-window offset reset |
| [solidjs/solid](https://github.com/solidjs/solid/pull/2783) | #2783 | Sync rejection from thenables reaches `<Errored>` |
| [solidjs/solid](https://github.com/solidjs/solid/pull/2782) | #2782 | Defer `onSettled` fallback cleanup |
| [solidjs/solid](https://github.com/solidjs/solid/pull/2781) | #2781 | SSR `lazy()` rejection handling |
| [cloudflare/workers-sdk](https://github.com/cloudflare/workers-sdk/pull/14286) | #14286 | Idempotent KV namespace provisioning |
| [livekit/agents-js](https://github.com/livekit/agents-js/pull/1765) | #1765 | Non-delta transcription final-stream races |
| [livekit/agents-js](https://github.com/livekit/agents-js/pull/1768) | #1768 | `SupervisedProc.initialize()` settle |
| [livekit/agents-js](https://github.com/livekit/agents-js/pull/1771) | #1771 | VAD-mode `minEndpointingDelay` |
| [prisma/prisma](https://github.com/prisma/prisma/pull/29634) | #29634 | `adapter-pg` 23505 driver error mapping |
| [PostHog/posthog-ios](https://github.com/PostHog/posthog-ios/pull/637) | #637 | `anonymousId` bootstrap |
| [PostHog/posthog-android](https://github.com/PostHog/posthog-android/pull/569) | #569 | `ignoredExceptionTypes` config for RN duplicates |
| [RevenueCat/purchases-ios](https://github.com/RevenueCat/purchases-ios/pull/6967) | #6967 | `PaywallView` customerInfo threading |
| [inngest/inngest-js](https://github.com/inngest/inngest-js/pull/1569) | #1569 | Map `step.ai.wrap` planned op |
| [anthropics/anthropic-sdk-typescript](https://github.com/anthropics/anthropic-sdk-typescript/pull/1089) | #1089 | Strip `anthropic-beta` on Vertex `count_tokens` |
| [MacPaw/OpenAI](https://github.com/MacPaw/OpenAI/pull/429) | #429 | Demo provider picker |
| [huggingface/transformers.js](https://github.com/huggingface/transformers.js/pull/1708) | #1708 | ONNX backend fallback on init failure |
| [colinhacks/zod](https://github.com/colinhacks/zod/pull/6082) | #6082 | RFC 6901 encoding for `$ref` JSON pointers |
| [getsentry/sentry-cocoa](https://github.com/getsentry/sentry-cocoa/pull/8048) | #8048 | Re-trigger feedback form across dismissals |
| [getsentry/sentry-cocoa](https://github.com/getsentry/sentry-cocoa/pull/8047) | #8047 | Dispatch `applicationState` to main thread on SDK init |

### Stack

- **iOS:** Swift + SwiftUI + StoreKit 2 + ActivityKit + WidgetKit + AVAudioEngine + ShazamKit + PencilKit + Core Bluetooth
- **AI / agent infra:** TypeScript + Python; reactive systems (SolidJS), agent frameworks (Mastra, LiveKit Agents, crewAI), inference SDKs (Anthropic, OpenAI), package managers (pnpm, unenv)
- **Backend:** Node / Python on Cloud Run + Fly.io + Hetzner
- **On-device voice:** Anthropic Claude (primary), WhisperKit + OpenVoice + Kokoro

### Contact

- Email: `t.sushanth@gmail.com`
- Open to conversations about iOS SDK / consumer mobile / applied-AI engineering roles
