KartoChaos - Folder Modeli 3D (.glb / .gltf / .obj)
======================================================

Podmiana modeli jest w pelni automatyczna - wystarczy nadpisac dowolny plik .glb w ponizszych katalogach:

1. public/models/karts/
   - interceptor.glb  (domyslny bolid z src/shared/data/karts.json)
   - buggy.glb        (pojazd terenowy)
   - titan.glb        (ciezki opancerzony kart)
   * Wskazowka: nazwij siatki wew. Blenderze jako KartBody / KartAccent / KartWheel_* aby zachowac
     malowanie 2D na zywo i obrot kol, lub uzyj wlasnych tekstur PBR!

2. public/models/powerups/
   - crate.glb        (skrzynka z bronią / powerupem na arenie)
   - rockets.glb, laser.glb, machinegun.glb, sentry.glb, nuke.glb, mine.glb, shield.glb, oil.glb,
     freezer.glb, hammer.glb, turbo.glb, emp.glb, plasma.glb, vortex.glb, vampire.glb, railgun.glb

3. public/models/props/
   - barrier.glb, pillar.glb, boost_pad.glb

Jezeli usuniesz dowolny plik .glb, silnik w trybie Smart Fallback automatycznie wyswietli
polprzezroczysty rozowy placeholder o wymiarach kolizji zamiast crasha gry.
