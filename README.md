# MovSG
Publication of MovieAD Dataset. MovieAD dataset is construct in conference paper "MovSG: Physical Transformation Rule Guided Photographic Film-to-Sound Generation Towards Film Protection".   

Photographic film to sound generation (PF2SG) refers to the process of generating movie sound from the photographic film roll, which is a key step in movie industry. Traditional PF2SG methods may lead irreversible physical damage to the flammable photographic film roll because of the scanning light in film projector. Nevertheless, current digital PF2SG methods typically generate lower quality results than traditional methods. This is due to the fact that these methods ignore the accumulated errors caused by various film damage. Facing these issues, instead of utilizing traditional laser scanning, we propose a novel PF2SG model, MovSG, to automatically and efficiently generate movie sound based on optical imaging and physical transformation rules, which can effectively protect the film. To the best of our knowledge, we take the first step to formalize the physical transformation rules involved in the PF2SG process. Specifically, the entire MovSG model consists of three stages: namely optical imaging based capturing, film-making-rule (FMR) guided pre-processing, and film-to-sound conversion rule (FSCR) guided sound generating. In the pre-processing stage, the captured image of photographic film is calibrated and restored to avoid accumulated errors. The sound generation stage takes the film image from the pre-processing stage and converts it to movie sound. To better evaluate MovSG, we build MovieAD2, the first dual mode photographic film soundtrack dataset, which contains photographic film images and the corresponding sound. Experimental results show that our method is two times faster than traditional PF2SG methods, while increasing the sampling rate to 162.08%.
