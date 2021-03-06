![SCORCH_Splash](Stimuli_TPWP.png)

# SCORCH_Dataset
This dataset was created for the purpose of having complex visual search stimuli under controlled conditions. Analogous to classic visual search tasks where the goal is to find a Gabor (target) in white/pink noise (background), this dataset provides a rich class of stimuli where the target is a person either armed or unarmed, in a scene background from an aerial point of view. Backgrounds were created with Virtual Battlespace 3 (VBS3) by Bohemia Interactive Simulations.

The goal of having targets (people) with and without weapons, beyond having an application to surveillance scenario tasks, is to enable more complex visual search experiments where the target can either be armed/unarmed and the distractors can either be unarmed/armed respectively. The hope of this stimuli is also to have subjects perform this task while finding the stimuli more natural than performing search of a Gabor signal in a noise background. Benchmarking visual search tasks & models with this dataset is encouraged.

Additional Features of this Dataset:

* Varying levels of clutter.
* Three levels of Zoom from the Aerial Point of View.
* Multiple target (person) appearances.
* Targets with and without weapon for friend and foe discrimination tasks.
* Scenes with target Present and Scenes with target Absent.
* Multiple Scene types with varying level of contrast (Night/Day time).

### Download RAW Video Dataset
$ wget -v -O SCORCH_Raw_Data.tgz -L https://ucsb.box.com/shared/static/h2xc3fbylxqt9epils1onsglyu2kere3.gz

### Download Stimuli used in the Attention Allocation Aid for Visual Search (2017) paper
$ wget -v -O AAAD_Stimuli.tgz -L https://ucsb.box.com/shared/static/vqfvrijvf3b08uqzxhjdys833camh7it.gz

More documentation such as target labels and (x,y) coordinates coming soon!

------

If you use the SCORCH Dataset please cite:

*@inproceedings{deza2017attention,*  
*title={Attention Allocation Aid for Visual Search},*  
*author={Deza, Arturo and Peters, Jeffrey R and Taylor, Grant S and Surana, Amit and Eckstein, Miguel P},*  
*booktitle={Proceedings of the 2017 CHI Conference on Human Factors in Computing Systems},*  
*pages={220--231},*  
*year={2017},*  
*organization={ACM}*  
*}*

