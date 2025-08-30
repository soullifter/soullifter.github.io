---
layout: splash
title: "Write Your Own Story"
permalink: /
# HERO
header:
  overlay_color: "#111"
  overlay_filter: "0.45"
  overlay_image: "https://images.unsplash.com/photo-1522071820081-009f0129c71c?q=80&w=1600&auto=format&fit=crop"
  actions:
    - label: "See Packages"
      url: "/packages/"
      class: "btn btn--primary"
    - label: "Subscribe Now"
      url: "/subscribe/"
      class: "btn"
# INTRO ROW (keeps your core line)
intro:
  - excerpt: |
      **You can write your own story.**  
      Not coaching. Not shortcuts. Just **guidance + accountability**.
# FEATURE ROW (your “What You’ll Get” bullets as tiles)
feature_row:
  - image_path: https://images.unsplash.com/photo-1585776245865-b92df54c6b25?q=80&w=1200&auto=format&fit=crop
    alt: "Clarity"
    title: "Clarity on Your Goals"
    excerpt: "We’ll sit together and break down your goals into **short-term, mid-term, and long-term** so there’s zero confusion about **what to do next**."
  - image_path: https://images.unsplash.com/photo-1506784983877-45594efa4cbe?q=80&w=1200&auto=format&fit=crop
    alt: "Weekly actions"
    title: "Weekly 2 Simple Actions"
    excerpt: "No long to-do lists. Commit to **just two small but powerful actions** every week to stay consistent without overwhelm."
  - image_path: https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1200&auto=format&fit=crop
    alt: "Accountability"
    title: "Guidance + Accountability"
    excerpt: "I won’t do it for you—but I’ll **show the path, track progress, and push when you slow down**. You’ll always know someone’s got your back."
# LINKS ROW (keeps your internal nav links)
cta_links:
  - excerpt: "👉 [Read My Story](/about/) · [Five Categories](/buckets/) · [See Packages](/packages/) · [Subscribe Now](/subscribe/)"
---

{% include feature_row id="intro" type="center" %}

<div class="reveal" markdown="1">
{% include feature_row %}
</div>

<div class="reveal" markdown="1">
### 💖 A Noble Cause
Path2Destiny is not just about guidance — it’s about **giving back**.  
**30%** of everything earned here goes to help people in need.  
When you start your journey, you’re also contributing to someone else’s.  
Together, we grow with good vibes. ✨
</div>

<div class="reveal" style="text-align:center; margin:28px 0 6px;">
  <p style="font-size:1.05rem; margin:0;">
    📺 <strong>All recorded sessions and regular updates</strong> will be available on our
    <a href="https://www.youtube.com/@yashwanthroyal5441" target="_blank" rel="noopener"><strong>YouTube channel</strong></a>.
  </p>
  <p style="opacity:.9; margin:.35rem 0 1rem;">
    Subscribe to get notifications the moment we post.
  </p>
</div>

<script>
  // simple scroll-reveal to match the new style
  const onScroll = () => {
    document.querySelectorAll('.reveal').forEach(el => {
      const r = el.getBoundingClientRect();
      if (r.top < window.innerHeight - 80) el.classList.add('is-visible');
    });
  };
  document.addEventListener('scroll', onScroll);
  document.addEventListener('DOMContentLoaded', onScroll);
</script>
