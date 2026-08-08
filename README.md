# Operations Lab — V1.4

Definitive fix for the mobile hero image.

The previous image file was not a pure photo: it was a composite containing the industrial photo AND the two Reliable/Resilient cards. Displaying it as a normal image therefore always showed the cards.

V1.4 creates a clean photo-only asset (`industrial-hero-photo.jpg`) from the photographic region and uses that asset in the hero.

No `background-size: cover` and no fixed mobile image height are used.
