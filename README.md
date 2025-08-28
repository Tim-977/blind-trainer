# Blindfold Memory Trainer

A simple, no-build trainer for practicing **blindfolded Rubik’s Cube letter sequences**.  
Made for fun, training, and possibly to live on [jperm.net](https://jperm.net/).

---

## What this is

When solving BLD (blindfolded) you need to **memorize long strings of letters** that correspond to edge and corner pieces. That’s what this trainer does:

- ✅ Generates real **edge** and **corner** letter sequences  
- ✅ Lets you pick **edges only**, **corners only**, or **both**  
- ✅ Lets you set the **length range** (min/max letters) or use presets (Easy / Normal / Extreme)  
- ✅ Supports different **buffers** 
- ✅ Optional **distraction task** simple math problem before recall (to imitate distractions during a real solve)
- ✅ Records **memorization time only** (from reveal → “Ready”)  
- ✅ Tracks accuracy, full solves, and last/median/average/best memorization times  
- ✅ Light/Dark theme toggle


### The best part: you can practice it without even having a Rubik’s Cube — just pure memory training

---

## Live Demo

👉 [Try it on GitHub Pages](https://tim-977.github.io/blind-trainer/)  

*(open on your phone or desktop browser, nothing to install)*

---

## How to use

1. Open the trainer.  
2. Pick your settings: edges/corners/both, buffer pieces, sequence lengths.  
3. Hit **Start**. Letters will appear.  
4. Memorize --> click **Ready**.  
5. If distraction is enabled, solve the math problem.  
6. Type your recalled sequence(s).  
7. See your accuracy and memo time.  
8. Hit **Next round** to continue, or **Reset stats** to wipe progress.

---

## For developers

- The widget is **one self-contained HTML file**: [`index.html`](./index.html).  
- Written in plain HTML + CSS + [jQuery](https://jquery.com/).  
- Drop-in ready: paste the `<div id="blindTrainer">…</div>` + `<script>…</script>` into any page that already loads jQuery.  
- Or embed as an `<iframe src="…/index.html">`.  
- Stats are saved in `localStorage`. No backend needed.  

---


## License

[MIT License](./LICENSE) – free to use, modify, and embed, as long as attribution is kept.  
© 2025 Timvkrns




## Feedback

If you have ideas, bug reports, or want to suggest features:  
- Contact me via project email --> blindtrainer@proton.me
- Open an [issue on GitHub](https://github.com/Tim-977/blind-trainer/issues)  



## Credits

Built by **Timvkrns**, inspired by J Perm.  
Made for the speedcubing community ❤️
