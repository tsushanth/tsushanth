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

Past few days I've been shipping fixes and small features across iOS / AI infrastructure repos I use in production:

| Repo | PR | Scope |
| --- | --- | --- |
| [anthropics/anthropic-sdk-typescript](https://github.com/anthropics/anthropic-sdk-typescript/pull/1087) | #1087 | `getContextWindowUtilization` helper |
| [vercel/ai](https://github.com/vercel/ai/pull/15943) | #15943 | `extractJsonMiddleware` leading-space fix |
| [realm/SwiftLint](https://github.com/realm/SwiftLint/pull/6768) | #6768 | `--parent-config` CLI flag |
| [GetStream/stream-chat-swift](https://github.com/GetStream/stream-chat-swift/pull/4127) | #4127 | Search-result icon |
| [airbnb/lottie-ios](https://github.com/airbnb/lottie-ios/pull/2688) | #2688 | IANA `.lot` extension support |
| [kean/Pulse](https://github.com/kean/Pulse/pull/371) | #371 | Opaque-image resize fix |
| [exyte/Chat](https://github.com/exyte/Chat/pull/282) | #282 | Dynamic Type username |
| [firebase/firebase-ios-sdk](https://github.com/firebase/firebase-ios-sdk/pull/16249) | #16249 | Analytics product disambiguation |
| [amplitude/Amplitude-Swift](https://github.com/amplitude/Amplitude-Swift/pull/411) | #411 | iOS 15 deployment target |
| [getsentry/sentry-cocoa](https://github.com/getsentry/sentry-cocoa/pull/8029) | #8029 | README install section |
| [superwall-me/Superwall-iOS](https://github.com/superwall/Superwall-iOS/pull/477) | #477 | macOS platform fix |
| [PostHog/posthog-ios](https://github.com/PostHog/posthog-ios/pull/637) | #637 | `anonymousId` bootstrap |
| [RevenueCat/purchases-ios](https://github.com/RevenueCat/purchases-ios/pull/6967) | #6967 | `PaywallView` customerInfo threading |
| [argmaxinc/argmax-oss-swift](https://github.com/argmaxinc/argmax-oss-swift/pull/487) | #487 | Sampler zero-probSum crash |
| [MacPaw/OpenAI](https://github.com/MacPaw/OpenAI/pull/429) | #429 | Demo provider picker |
| [ml-explore/mlx-swift-examples](https://github.com/ml-explore/mlx-swift-examples/pull/481) | #481 | `image-tool` README |

### Stack

- **iOS:** Swift + SwiftUI + StoreKit 2 + ActivityKit + WidgetKit + AVAudioEngine + ShazamKit + PencilKit + Core Bluetooth
- **Backend:** Node / Python, deployed on Cloud Run + Fly.io
- **AI:** Anthropic Claude (primary), WhisperKit + OpenVoice + Kokoro for on-device voice

### Contact

- Email: `t.sushanth@gmail.com`
- Open to conversations about iOS SDK / consumer mobile / applied-AI engineering roles
