---
title: "`autoGainControl`、`noiseSuppression` メディアトラック制約の接頭辞が外れました"
date: "2017-05-21T23:41:00-05:00"
categories: ["audio-video"]
tags: []
versions: ["55"]
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1366415"
      title: "Bug 1366415 - Unprefix autoGainControl and noiseSuppression constraints"
---
[`MediaTrackConstraints`](https://developer.mozilla.org/docs/Web/API/MediaTrackConstraints) ディクショナリー上の `autoGainControl`、`noiseSuppression` 両プロパティが接頭辞なしで使用可能となりました。それらの `moz` 接頭辞付きバージョンは近い将来削除されます。

**更新**: 接頭辞付き制約は [Firefox 64 で削除されました](https://www.fxsitecompat.com/ja/docs/2018/prefixed-autogaincontrol-and-noisesuppression-media-track-constraints-have-been-removed/)。
