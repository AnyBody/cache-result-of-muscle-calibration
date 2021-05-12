# Cache result of muscle calibration

The three element muscle model is sensitive to tendon slack length variable (Lt0). Therefore, tendon slack length 
must be calibrated to ensure that the optimal muscle fiber length occurs at the desired/specified joint angle.

The problem, however, is that the calibration procedure can take a while to run. This presents an overhead when running many multiple models with the same scaling. 
The solution is to save the result of the calibration procedure and just load those results for later.


This small example model shows how to save the result of a calibration procedure so it can be reused in other models.

![image](https://user-images.githubusercontent.com/1038978/117982217-152feb80-b336-11eb-96b1-cc4a5aad38f0.png)
