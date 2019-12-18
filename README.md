# pix2pixGAN
Computer vision final project
\n
python test.py --dataroot ./datasets/dog/ --direction AtoB --model pix2pix --name dog_pix2pix
\n
python train.py --dataroot ./datasets/mydog --name mydog_pix2pix --model pix2pix --direction AtoB
\n
python test.py --dataroot ./datasets/Demo/ --direction AtoB --model pix2pix --name mydog_pix2pix
\n
(hed detector)
\n
python test.py --dataroot ./datasets/Demo_hed/ --direction AtoB --model pix2pix --name dog_pix2pix
\n
(canny detector)
\n
python test.py --dataroot ./datasets/Demo/ --direction AtoB --model pix2pix --name Demo_pix2pix
\n
(Xming setting)
\n
export Display:=0
