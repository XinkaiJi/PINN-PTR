# PINN-PTR
The official codebase for the paper "Physics-Informed Neural Network for Trajectory Reconstruction: A Hybrid Paradigm Informed by Car-Following Models"

The source code is currently being organized and will be open-sourced and uploaded soon.

## Dataset
The Single-Lane Dataset has already been open-sourced. You can download it at: [https://swiftraj.com/download.html](https://swiftraj.com/download.html).

The data were collected on the Nanjing Inner Ring West Line, an elevated segment of Nanjing’s urban expressway network. The study section is configured as a two-way, two-lane roadway, with one lane per direction, meaning that lane-changing maneuvers are not possible within the observed area. Two UAVs were deployed simultaneously to record the traffic scene, and the videos were subsequently stitched in post-processing to obtain continuous vehicle trajectories. For the data collected on November 1, the resulting trajectories cover an approximately 1,000 m road segment and include six independent collection sessions, labeled F1–F6. In particular, session F5 was captured with the road segment arranged diagonally in the image frame, aiming to extend the observable road coverage and obtain a longer trajectory extraction range. For the data collected on November 14, the resulting trajectories cover an approximately 700 m road segment and include three independent collection sessions, labeled AD, BE, and CF.

## Citation
If you use this code or dataset in your research, please cite our paper:

```bibtex
@ARTICLE{11495051,
  author={Ji, Xinkai and Liu, Pan and Han, Yu},
  journal={IEEE Transactions on Intelligent Transportation Systems}, 
  title={Physics-Informed Neural Network for Trajectory Reconstruction: A Hybrid Paradigm Informed by Car-Following Models}, 
  year={2026},
  volume={},
  number={},
  pages={1-17},
  doi={10.1109/TITS.2026.3686011}
}
```
