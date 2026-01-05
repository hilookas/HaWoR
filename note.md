```bash
sudo apt-get install -y libxcb-icccm4 libxcb-image0 libxcb-keysyms1 libxcb-render-util0 libxcb-xkb1 libxkbcommon-x11-0 libxcb-xinerama0
sudo apt-get install -y libegl1 libgl1-mesa-glx libgles2 libglvnd0 mesa-vulkan-drivers
sudo apt-get install -y libgl1 libglu1-mesa mesa-utils libgl1-mesa-dev
ldconfig -p | grep libGL

python demo.py --video_path ./example/video_0.mp4  --vis_mode world
```