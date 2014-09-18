---
layout: post
title: "Renderscript Reference Material"
date: 2014-09-13 14:48:17 -0400
comments: true
categories: renderscript, UI, UX
published: false 

---

<!-- Renderscripted Custom Views, References -->

### 'Renderscripted' Custom Views, References

Here are all the various sources of information I used while working on this project. 

#### FFT Implementation

I've just found this [renderScriptFFT project](https://github.com/nesl/renderScriptFFT) on github, it looks like it's a working implementation of the idea I had writing part 2/5. I will use it more for inspiration rather than spawn off a copy of it.

Again for the FFT segment, an old series of java articles ([part 1](http://www.developer.com/java/other/article.php/3380031/Spectrum-Analysis-using-Java-Sampling-Frequency-Folding-Frequency-and-the-FFT-Algorithm.htm) and [part 2](http://www.developer.com/java/other/article.php/3374611/Fun-with-Java-How-and-Why-Spectral-Analysis-Works.htm)) that explain spectrum analysis in layman's terms. 

#### Misc. Reading Notes

Likely not everything I've researched will make it in the series, but here are my reading notes for future reference.

One thing I've been thinking a lot about is the [Masagin Demo](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0CCAQyCkwAA&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DsbQhgEJuExY&ei=DZQUVK2CDISQyAT4yYCQBQ&usg=AFQjCNEbUqvGzjfFwDKHiddDXbzJK1fMIw&sig2=6y7ydhkAjq3gun95FbrYQg&bvm=bv.75097201,d.aWw) and how much I love that infinite zoomer into scalable vector graphics effect. That effect could perhaps be replicated with the standard AOSP APIs, but if not, there's something Renderscript could probably help with. This [medium post](https://medium.com/@romainguy/androids-font-renderer-c368bbde87d9) by Romain Guy keeps coming up in my related searches, and I have to dig up another video post I saw a few months ago that explored other real-time rendering options with TTF, it seemed very promising. After some digging, I believe [Glyphy](http://vimeo.com/83732058) was the item in question. It was a shader-based approach to rendering fonts. 

One thing I will need to find out is how good the RS methods I propose will perform VS GPU rendering tricks. Also, it looks like we could be treated to some sort of OpenCL / Cuda implementation when/if someone comes out with a NVidia K1 backed Android TV...