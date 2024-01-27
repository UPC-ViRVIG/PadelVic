# PadelVic
Padel-specific collection of datasets targeted to train and test computer vision applications on padel videos

## Captured datasets
| Dataset    | Height | Device              | Resolution | FPS | Format | Link |
|------------|--------|---------------------|------------|-----|--------|------|
| Main camera        | 6 m    | Panasonic AG-UX180 4K | 3840x2160 | 50  | MP4    | [3626x1960 version, 5.2 GB](https://www.dropbox.com/scl/fi/hrzytt71wc92zaq8oq0fh/panasonic_final.mp4?rlkey=vhj3rp9xbmxhemmx24bkfnu55&dl=0) |
| Second camera      | 7.5 m  | GoPro Hero9 Black     | 3840x2160 | 60  | MP4    | [2806x1870 version, 5.2 GB](https://www.dropbox.com/scl/fi/pnzk74zghdxtybd9zb62a/gopro.mp4?rlkey=k3agl6p3ntigncx0dbu0jwu2e&dl=0) |
| Court level 1      | 1.45 m | Samsung Galaxy S22+  | 1920x1080 | 60  | MP4    | [1920x1080 version, 3.2 GB](https://www.dropbox.com/s/hn9ub1qmjurcf5b/samsung.mp4?dl=0)|
| Court level 2      | 1.45 m | iPhone 13 Pro Max    | 1920x1080 | 60  | MOV    | [1920x1080 version, 3.2 GB](https://www.dropbox.com/scl/fi/6n7ahs5az28sos3pws7dg/iphone.mp4?rlkey=vn6hfwoz84k60w5ug1nyo2uiz&dl=0)|
| Motion Capture     | N/A    | Xsens MVN Awinda      | N/A       | 60  | BVH| [One player, all games, 183 MB](https://www.dropbox.com/scl/fi/sl5hdlr6bal69v2acdbei/bvh.zip?rlkey=13ttllqg65ayoujhozpy75yzd&dl=0)|

## Synthethic videos (and CSV files with ground truth positions)
| Dataset    | Source              | Format | Link |
|------------|---------------------|--------|------|
| 1 player @bottom, no court | Xsens MVN Awinda      | MP4 | [Sample, 29 MB](https://www.dropbox.com/scl/fi/clsjqiwvby6w8byv9g0ap/1630-16300.mp4?rlkey=aqecxe72tasojmoqi721l6mdv&dl=0) |
| 1 player @bottom, court, GT position sphere| Xsens MVN Awinda | MKV | [Sample, 9 MB](https://www.dropbox.com/scl/fi/lv1itp4vpnwywudwe6t6b/001-2200-3960.mkv?rlkey=fm1544hw7gwzzcw8ly9ulfyku&dl=0) |     
| 1 player @bottom, court | Xsens MVN Awinda | MKV | [001: Two rallies, 88 MB](https://www.dropbox.com/scl/fi/hhw2ag7nfligagrgu01nm/001-1250-17462.mkv?rlkey=9pcmp205da9ifanqxr1uc99ox&dl=0) [CSV with GT positions](https://www.dropbox.com/scl/fi/84pppfrg8h263q91wr9vv/001-1250-17462.csv?rlkey=48cs2qs15cdq7pt28qzxfkfjt&dl=0)|     
| 1 player @bottom, court | Xsens MVN Awinda | MKV | [002: One rally, 61 MB](https://www.dropbox.com/scl/fi/1v5gi1sz331f6vwwaqer2/002-0275-11541.mkv?rlkey=fva50ssaofd5c2v0xpdxxn4va&dl=0) [CSV with GT positions](https://www.dropbox.com/scl/fi/1rea3wuis3cv12pf6fwts/002-0275-11541.csv?rlkey=wk9yvlikw2jzw19if6ckc3bzw&dl=0)|   
| 1 player @top, court | Xsens MVN Awinda | MKV | [002: One rally, 60 MB](https://www.dropbox.com/scl/fi/tb94z4sm8s2oeufwtb9fy/002B-0275-11541.mkv?rlkey=91ddt8bxhl41gfj33ynw3e52x&dl=0) [CSV with GT positions](https://www.dropbox.com/scl/fi/qku3xtfekqia0ar1mlgdv/002B-0275-11541.csv?rlkey=c0bgzjtwf0zcdspqrkbtbnbzo&dl=0)|   


## Derived data (human detection and pose estimation from video)
| Dataset    | Source              | Format | Link |
|------------|---------------------|--------|------|
| Player tracking results | Panasonic AG-UX180 4K | MP4    | [Sample, Game 2, 16MB](https://www.dropbox.com/scl/fi/oelg2ildoat14ttf4asv0/game2_vic_panasonic.mp4?rlkey=snv6msx10usvaq6nnl47v4cij&dl=0) |
| Player positions        | Panasonic AG-UX180 4K | XLSX    | [Sample, 550 KB](https://www.dropbox.com/scl/fi/g8usouvynhxb8jkoumqop/PadelVic_Panasonic_labeling-all-shared.xlsx?rlkey=5zs59cg3q4doiio75bak5255h&dl=0) |
| Player poses        | Panasonic AG-UX180 4K | JSON    | [Sample, 74 MB](https://www.dropbox.com/scl/fi/tkbeu8ndxl4axy9iijcwt/Panasonic_Poses.zip?rlkey=q9c60m5ln85nrihum1tlq4q53&dl=0) |



> [!NOTE]
> The player positions and player poses datasets above are just a sample, computed with a work-in-progress, non-robust player tracking method.  

## How to cite
"PADELVIC: Multicamera videos and motion capture data of an amateur padel match", by Mohammadreza Javadiha, Carlos Andujar, Michele Calvanese, Enrique Lacasa,
Jordi Moyés, Jose Luis Ponton, Antonio Susín and Jiabo Wang. 
Padel Scientific Journal 2 (1), 89-106, 2024. 
[DOI 10.17398/2952-2218.2.89](https://doi.org/10.17398/2952-2218.2.89)

## Licence
This dataset can be used only for research purposes. More details on the CC-BY-like license coming soon. 
