# pix2pixGAN
Computer vision final project
python test.py --dataroot ./datasets/dog/ --direction AtoB --model pix2pix --name dog_pix2pix
python train.py --dataroot ./datasets/mydog --name mydog_pix2pix --model pix2pix --direction AtoB
python test.py --dataroot ./datasets/Demo/ --direction AtoB --model pix2pix --name mydog_pix2pix
(hed detector)
python test.py --dataroot ./datasets/Demo_hed/ --direction AtoB --model pix2pix --name dog_pix2pix
(canny detector)
python test.py --dataroot ./datasets/Demo/ --direction AtoB --model pix2pix --name Demo_pix2pix
(Xming setting)
export Display:=0
