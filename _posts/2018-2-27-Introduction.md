---
layout: post
title: Motivated Text
author:     Paul Warren
thumbnail:  heart
---

### What did Text ever do to you?

The aim of this blog is document my experiments with animating text presentation. This is intended to go well beyond the usual ideas of simply having text fade in or fade out or maybe flying in from the left or the right or even zooming or shrinking to a size.

# smaller header

     func createGlyphLayers() {
        assert(Thread.isMainThread)
        guard let text = self.text else { return }
        
        if let sublayers = self.layer.sublayers {
            for sublayer in sublayers {
                sublayer.removeAllAnimations()
                sublayer.removeFromSuperlayer()
            }
        }

I'm hoping to achieve something more cinematic, inspired largely by Movie and TV titles, where the presentation of the characters or strings is an integral part of the art or mood of the piece. Think bold Sci-fi fonts wiggling into view as if shown on an old poorly tuned TV screen or the scrolling opening roll from Star Wars, or the spiky bold lettering from Vertigo.

That's what I'm going to try to replicate. A big influence on this endeavor are the titles for the show **Jonathan Strange & Mr Norrell**, which have a fluid period feel but also portray the mood of the piece by being both slightly magical, in their fading appearance, and whimsical in the many varied ways they start to disappear, as if wished away by an unseen magical force (I know is seems fanciful but the effect works really well)

Well, my results might not be magical but it's worth a try, and hopefully a fun learning experience along the way.
