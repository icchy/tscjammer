# tscjammer
tscjammer is reference implementation for [VMMを用いたタイミングベースサイドチャネル攻撃に対する緩和策](https://www.slideshare.net/icchyr/vmm-185190920) (Japanese onliy) in CSS2019 demonstration.
This project is based on [BitVisor](https://www.bitvisor.org).
## Usage
### change noise level
```
cd tools/test; make
./test <noise level> # default: 0
```
