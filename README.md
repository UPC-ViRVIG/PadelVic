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

## Synthethic videos
| Dataset    | Source              | Format | Link |
|------------|---------------------|--------|------|
| No court | Xsens MVN Awinda      | MP4 | [Sample, 29 MB](https://www.dropbox.com/scl/fi/clsjqiwvby6w8byv9g0ap/1630-16300.mp4?rlkey=aqecxe72tasojmoqi721l6mdv&dl=0) |
| Court, ground truth position | Xsens MVN Awinda | MKV | [Sample, 9 MB](https://www.dropbox.com/scl/fi/lv1itp4vpnwywudwe6t6b/001-2200-3960.mkv?rlkey=fm1544hw7gwzzcw8ly9ulfyku&dl=0) |     
| Court | Xsens MVN Awinda | MKV | [Two rallies, 88 MB](https://www.dropbox.com/scl/fi/hhw2ag7nfligagrgu01nm/001-1250-17462.mkv?rlkey=9pcmp205da9ifanqxr1uc99ox&dl=0) [CSV with GT positions](https://www.dropbox.com/scl/fi/84pppfrg8h263q91wr9vv/001-1250-17462.csv?rlkey=48cs2qs15cdq7pt28qzxfkfjt&dl=0)|     

## Derived data (human detection and pose estimation from video)
| Dataset    | Source              | Format | Link |
|------------|---------------------|--------|------|
| Player positions        | Panasonic AG-UX180 4K | XLSX    | [Sample, 423 KB](https://www.dropbox.com/scl/fi/3yo9y12h2p71syxul1u7d/Panasonic_labeling.xlsx?rlkey=lk0psr7kap2qoy3d3kw8gcvba&dl=0) |
| Player poses        | Panasonic AG-UX180 4K | JSON    | [Sample, 74 MB](https://www.dropbox.com/scl/fi/tkbeu8ndxl4axy9iijcwt/Panasonic_Poses.zip?rlkey=q9c60m5ln85nrihum1tlq4q53&dl=0) |
 

## How to cite
"PadelVic: A Multimodal Dataset of an Amateur Padel Match", by Mohammadreza Javadiha, Carlos Andujar, Michele Calvanese, Enrique Lacasa,
Jordi Moyés, Jose Luis Ponton, Antonio Susín and Jiabo Wang. I Congreso Nacional de Padel, Cáceres, 15-16 sep 2023. 

## Licence
This dataset can be used only for research purposes. More details on the CC-BY-like license coming soon. 
