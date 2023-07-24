# Combining Smart Speaker and Smart Meter to Infer Your Residential Power Usage by Self-supervised Cross-modal Learning

## Important Date

- [ ] Release the power data in the self-collected dataset (2023-7-28)
- [ ] Release the acoustic data in the self-collected dataset (2023-9-15)

## Dataset
This dataset contains appliance power data and acoustic data collected from 6 houses.
Use the links below to download the:
* [Real world power dataset](https://www.dropbox.com/scl/fi/qjze62x99v8zeicuh5hu2/Raw_Power_Data_New.zip?rlkey=xk45m2jlaizmckssfdd4w409j&dl=0) (Appliance power data)
* [Real world acoustic dataset](https://www.dropbox.com/scl/fi/3uaq6hg2zbkt6mt6yshq2/Csv_Sound_Data_New.zip?rlkey=13gy8f2697997pi9gbvmcy5kc&dl=0) (Not labeled acoustic data)
* [Real world acoustic dataset of appliances](https://www.dropbox.com/scl/fi/ice55pvgnokc7u3we5uba/Csv_Sound_Labeled_New.zip?rlkey=x8zyyxvabdwdnk2kh30jhtkrw&dl=0) (Appliance related acoustic data)
  
Dataset directory structure：
```
power_data/
|----Room_1/
|    |----refrigerator.csv
|    |----microwave.csv/
|    |----...
|----...

acoustic_data/
|----Room_1/
|    |----overlap/
|         |----Oven
|              |----2022-06-04-20-26-43.csv
|              |----...
|         |----microwave
|              |----2022-06-04-20-46-17.csv
|              |----...
|         |----...
|    |----non-overlap/
|         |----...
|    |----all/
|         |----...
|----...
```	

## Contact Information
guanzhou.zhu@bupt.edu.cn
