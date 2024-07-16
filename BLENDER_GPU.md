# Blender GPU

## Karty graficzne (gamingowe)

- NVIDIA Gforce RTX 3090Ti, 4060Ti szybsze od radeonów RX 7600 Xt
- 4060 170% faster in classroom demo render
- 3090 60s RTX do 170s RX  Nvidia faster in classroom demo render
- Blender wykorzystuje wiele kart GPU bezproblemowo (na płytach bez certyfikatu SLI i bez mostkowania SLI, Crossfire)

## EGPU do laptopa

- Raczej unikać ograniczenie transferu do 40GB/s i kilka innych problemów
- A jeżeli już to karty NVIDIA

## Cykle render

- Cykle się słabo skaluje przy wielu kartach
- Renderuje w czasie podobnym do Octane Render
- Lepiej działa z NVIDIA

## Octane render

- Octane skaluje się z wieloma kartami
- Kilka kart bez SLI do 8 kart wzrost wydajności do 100% na kartę
- Renderuje w czasie podobnym do Cykle (subsurface lepsze w Octane)
- Wmaga NVIDIA RTX z CUDA
- Najwydajniej RTX z Optix

## CUDA vs OptiX

- CUDA wzrost wydajności niemal 100% przy 2 kartach
- OptiX wzrost wydajności mniejsza niż 100% przy 2 kartach ale szybciej renderuje

## Links

- <https://youtu.be/NvXnbHPi-sQ?t=762>
- <https://www.youtube.com/watch?v=Kdc7OKQkVmw>
