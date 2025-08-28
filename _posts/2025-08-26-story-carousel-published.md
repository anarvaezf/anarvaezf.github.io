---

layout: default
title: "Story\_carousel: Instagram-like stories for Flutter"
description: A simple package to add Instagram-style stories to your Flutter apps.
tags: \[flutter, packages, pubdev]
----------------------------------

If you’ve ever wanted to add **Instagram-style stories** to your Flutter app, you know it’s not something included out-of-the-box.
That’s why I created **story\_carousel**, a lightweight package that brings a familiar stories experience to any Flutter project.

---

## Why I built it

While working on personal projects, I needed a **carousel of “stories”** that supported:

* Automatic playback
* Tap gestures to move forward/backward
* Long-press to pause
* A progress indicator for each story

I couldn’t find a simple and flexible solution, so I built one and published it on **pub.dev**.

---

## When to use it

This widget is useful in apps that want to display content in quick, snackable formats, such as:

* **Social apps** (stories, highlights, announcements)
* **E-learning** (step-by-step guides or mini-lessons)
* **News / media apps** (headlines, daily digests)
* **Internal business tools** (onboarding flows, quick updates)

Basically, anywhere you want users to consume content in a **visual, swipeable format**.

---

## Getting started

You can install it directly from pub.dev:

```bash
flutter pub add story_carousel
```

Example usage:

```dart
StoryCarousel(
  title: 'Demo Stories',
  items: const [
    Image(image: NetworkImage('https://picsum.photos/600/900?1')),
    Center(child: Text('Free text / any widget')),
    Image(image: NetworkImage('https://picsum.photos/600/900?2')),
  ],
  autoPlay: true,
  loop: true,
);
```

That’s it — you now have stories in your Flutter app.

---

## Learn more

For advanced usage, like controlling playback programmatically, customizing durations, or running the example app, check out:

* 📦 Pub.dev: [story\_carousel](https://pub.dev/packages/story_carousel)
* 💻 GitHub: [anarvaezf/flutter\_story\_carousel](https://github.com/anarvaezf/flutter_story_carousel)

---

## Final thoughts

This is my **first Flutter package published on pub.dev**, and I’m excited to keep improving it.
If you try it, I’d love to hear your feedback — PRs and issues are always welcome!
