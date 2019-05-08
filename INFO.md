# Translation progress


| Chapter              | Progress | Owner | Last status update date |
| -------------------- | -------- | ----- | --- |
| chapter_introduction | 0.5.0 ready | Kyoungsu | 9th Apr 2019 |
| chapter_crashcourse | 0.5.0 ready | Muhyun | 9th Apr 2019 |
| chapter_deep-learning-basics | reflecting 0.6.0 | Muhyun | 12rd Apr 2019 |
| chapter_deep-learning-computation | 0.5.0 ready | Muhyun | 9th Apr 2019 |
| chapter_convolutional-neural-networks | draft in progress | Muhyun |9th Apr 2019|
| chapter_recurrent-neural-networks | not yet started | TBD |9th Apr 2019|
| chapter_optimization |not yet started|TBD|9th Apr 2019|
| chapter_computational-performance |not yet started|TBD|9th Apr 2019|
| chapter_computer-vision |not yet started|Jiyang|15th Apr 2019|
| chapter_natural-language-processing |not yet started|Jihye|15th Apr 2019|
| chapter_appendix |not yet started|TBD|9th Apr 2019|

# BUILD PDF

Needs to install Korean fonts. On Linux, we can do

```
wget https://github.com/adobe-fonts/source-han-sans/raw/release/OTF/SourceHanSansK.zip
wget https://github.com/adobe-fonts/source-han-serif/raw/release/OTF/SourceHanSerifK_SB-H.zip
wget https://github.com/adobe-fonts/source-han-serif/raw/release/OTF/SourceHanSerifK_EL-M.zip

unzip SourceHanSansK.zip
unzip SourceHanSerifK_EL-M.zip
unzip SourceHanSerifK_SB-H.zip

sudo mv SourceHanSansK SourceHanSerifK_EL-M SourceHanSerifK_SB-H /usr/share/fonts/opentype/
sudo fc-cache -f -v
```
