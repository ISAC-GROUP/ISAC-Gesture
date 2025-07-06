# ISAC-Group Acoustic-based gesture dataset


The dataset contains a series of gesture data perceived by sound waves for gesture recognition and related research.


## 📚Content

- **Gesture type:** digits(0-9, 10 kinds), capital letters(A-Z, 26 kinds), self-defined gestures(8 kinds).

- **Number of spectrograms:** 86,752.

- **Collecting device:** mainly Samsung Galaxy Tab S2; very few are Oppo watch and Xiaomi phone.

- The specific details include orientation, environment, posture and distance. If further clarification is needed, please feel free to contact the author.

- **Example:**

  Letter"A", Samsung Tab, 0°, lab environment, in-hand:    [p1-sss-0-1-lab-hand-18.png] ![p1-sss-0-1-lab-hand-18](p1-sss-0-1-lab-hand-18.png)

  Digit"0", Oppo watch, 0°, lab environment, on-table:   [p11-watch-0-1-lab-none-17.png] ![p11-watch-0-1-lab-none-17](p11-watch-0-1-lab-none-17.png)


## ⚙️File Structure

```bash
- /
  ├── /digits
  │   ├── /0
  │   │   ├── p1-sss-0-1-lab-hand-1.png
  │   │   ├── p11-watch-0-1-lab-none-2.png
  │   │   └── ...
  │   ├── /1
  │   │   ├── ...
  │   ├── /2
  │   │   └── ...
  │   └── ...
  ├── /extension gestures
  │   ├── /gesture0
  │   │   ├── p2-sss-0-1-lab-none-new-46.png
  │   │   ├── p3-sss-0-1-lab-none-new-14.png
  │   │   └── ...
  │   ├── /gesture1
  │   │   ├── ...
  │   │   └── ...
  │   └── ...
  └── /letters
      ├── /A
      │   ├── p1-sss-0-1-lab-hand-1.png
      │   ├── p1-sss-0-1-lab-hand-2.png
      │   └── ...
      ├── /B
      │   └── ...
      └── ...
```


## ✔️Usage

1. **Download**: Clone or download the dataset locally. **Due to the large number of files, we have placed the data for letters "K" to "Z" on Google Drive.**

```bash
git clone https://github.com/ISAC-GROUP/ISAC-Gesture.git
```

```bash
https://drive.google.com/drive/folders/1GvJN01FuhGpSDl0oNmU7xCZbxltt-iae?usp=sharing
```

2. **Data format:** Data sets are stored as image files in their respective category folders.

```bash
p11    -    watch    -    0    -    1    -    lab    -    none    -    20     .png
 │            │           │         │          │            │           │      │              
user       device    orientation distance  environment   posture      count  format
     
```

3. **Citation:** If you have used this dataset in your research, please refer to this dataset.


## 🔗Citation

**If you have used this dataset, please cite the following information:**

> https://github.com/ISAC-GROUP/ISAC-Gesture

> Zou Y, Wang Y, Dong H, et al. PreGesNet: Few-shot Acoustic Gesture Recognition Based on Task-adaptive Pretrained Networks[J]. IEEE Transactions on Mobile Computing, 2024.

## 😀Contact information

**If you have any questions or feedback, please feel free to contact us:**

- Author：[Yongpan Zou(邹永攀), Yunshu Wang(王云舒), Yanbo He(何彦博)]
- E-mail: [yongpan@szu.edu.cn; wangyunshu2018@email.szu.edu.cn; yanboheszu@gmail.com]
- Address: College of Computer Science and Software Engineering, Shenzhen University, 3688 Nanhai Ave, Shenzhen, Guangdong, China, 518060.

Thank you for using our dataset!

---


## 🆕Update at 2024/04/11

The updated data include four newly recruited participants who perform custom gestures within five weeks, as well as data from three participants who participated in the experiment one year ago and perform custom gestures again. The total amount of data is 3263 samples, expected to be helpful for long-term research.

🔗 **Access the new dataset here:**

```bash
https://drive.google.com/drive/folders/1VU5LvRAw_kjCxLmkWiLYDcn0oCEz9vyO?usp=drive_link
```

---

## 🆕Update at 2024/12/14

Our paper has been accepted by IEEE TMC: Y. Zou, Y. Wang, H. Dong, Y. Wang, Y. He and K. Wu, "PreGesNet:  Few-Shot Acoustic Gesture Recognition Based on Task-Adaptive Pretrained Networks,"  in IEEE Transactions on Mobile Computing, vol. 23, no. 12, pp. 12811-12829, Dec. 2024, doi: 10.1109/TMC.2024.3419556

---

## 🆕Update at 2025/07/06

🔗 **Access the code repository here:**

```bash
https://drive.google.com/drive/u/1/folders/1wi_tnkHeY6yvyHhvRvCCj1Xklq8DBkx4
```

---
