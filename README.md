# Raster Image Optimization

---

**Author :** Fesal Badday

**Repo :** [Github Repo](https://github.com/FesalBadday/raster-image-optimization)

**Site :** [Github Pages](https://FesalBadday.github.io/raster-image-optimization)

**Information :**

- A collection of an open source images of Nature.

---

## Attributions
- [Lake With Mountain View](https://www.pexels.com/photo/lake-with-mountain-view-2440021) By [Ian Beckley](https://www.pexels.com/@ian-beckley-1278367) Under [Pexels License](https://www.pexels.com/license)
- [2 People On The Boat](https://www.pexels.com/photo/2-people-on-the-boat-2166711) By [Quang Nguyen Vinh](https://www.pexels.com/@quang-nguyen-vinh-222549) Under [Pexels License](https://www.pexels.com/license)
- [Clearwater With Reflection And Fog](https://www.pexels.com/photo/photo-of-body-of-water-2649403) By [Quang Nguyen Vinh](https://www.pexels.com/@quang-nguyen-vinh-222549) Under [Pexels License](https://www.pexels.com/license)
- Credits to [Ashley Knox](https://github.com/lilyx13) For using the below code.
```
<img src="path/img-sm.webp"
  srcset="path/img-sm.webp 320w,
    path/img-md.webp 800w,
    path/img-lg.webp 1200w"
  sizes="(min-width: 960px) 80vw,
         (min-width: 640px) 90vw,
         100vw"
  alt="img description>

.container {
  width: 90vw;
  max-width: 1920px;
  margin: auto;
}

img {
  width: 100%;
  height: auto;
  aspect-ratio: attr(width) / attr(height);
}
```