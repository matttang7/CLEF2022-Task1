# CLEF2022--CheckThat-Lab
This repository contains the _dataset_, _format checker, scorer and baselines_ for the [CLEF2022-CheckThat! Lab](https://sites.google.com/view/clef2022-checkthat).
The shared task focuses on detecting check-worthy claims, previously fact-checked claims, and fake news.
The CLEF2022-CheckThat! Lab has three main tasks each offered in variety of languages:

  - [Task 1: Identifying Relevant Claims in Tweets](task1)
    - Subtask 1A: Check-worthiness estimation
      - **Arabic**
      - **Bulgarian**
      - **Dutch**      
      - **English**
      - **Spanish**
      - **Turkish**
    - Subtask 1B: Verifiable  factual  claims  detection
      - **Arabic**
      - **Bulgarian**
      - **Dutch**      
      - **English**
    - Subtask 1C: Harmful tweet detection
      - **Arabic**
      - **Bulgarian**
      - **Dutch**      
      - **English**
    - Subtask 1D: Attention-worthy  tweet  detection
      - **Arabic**
      - **Bulgarian**
      - **Dutch**      
      - **English**
  - [Task 2: Detecting Previously Fact-Checked Claims](task2)
    - Subtask 2A: Detect Previously Fact-Checked Claims in Tweets
      - **Arabic**
      - **English**
    - Subtask 2B: Detect Previously Fact-Checked Claims in Political Debates/Speeches
      - **English**
  - [Task 3: Fake News Detection](task3)
      - **English**
      - **German**

<!-- # Leaderboard

## Task 1
Kindly find the leaderboard released in this google sheet, [link](https://tinyurl.com/kfmawuke). you can find in the tab labeled "Task 1".

## Task 2
Kindly find the leaderboard released in this google sheet, [link](https://tinyurl.com/kfmawuke). you can find in the tab labeled "Task 2".


# Submission sites
## Task 1 -->

<!-- Submission Guidelines:
- Make sure that you create one account for each team, and submit it through one account only.
- The last file submitted to the leaderboard will be considered as the final submission.
- The output file has to have a `.tsv` extension; otherwise, you will get an error on the leaderboard.
- You need to write a small description of the model submitted in a `.txt` file.
- You have to zip the tsv, `zip submission.zip path_to_tsv_pred_file_1.tsv path_to_tsv_pred_file_2.tsv ... path_to_tsv_pred_file_n.tsv model_description.txt` and submit it through the codalab page. -->

<!-- All leaderboard for dev and test data can be found here, https://competitions.codalab.org/competitions/30853. -->

<!-- **NOTE**: The leaderboard for the Spanish test data is found in a separate leaderboard, https://competitions.codalab.org/competitions/31262. -->

<!-- ## Task 2

Submission Guidelines:
- Make sure that you create one account for each team, and submit it through one account only.
- The last file submitted to the leaderboard will be considered as the final submission.
- The output file has to have a `.tsv` extension; otherwise, you will get an error on the leaderboard.
- You need to write a small description of the model submitted in a `.txt` file.
- You have to zip the tsv, `zip submission.zip path_to_tsv_file.tsv model_description.txt` and submit it through the codalab page.

All leaderboards for dev and test data can be found here, https://competitions.codalab.org/competitions/30949. -->

# Licensing

These datasets are free for general research use.

# Credits

Lab Organizers:

Task website: https://sites.google.com/view/clef2022-checkthat

Contact:   clef-factcheck@googlegroups.com

# Citation

You can find the overview paper on the CLEF2022-CheckThat! Lab in the paper, "The CLEF-2022 CheckThat! Lab on Fighting the COVID-19 Infodemic and Fake News Detection".

<!-- ```
@InProceedings{​​​​​​​CheckThat:ECIR2022,
  author    = {​​​​​​​Preslav Nakov and
               Da San Martino, Giovanni and
               Tamer Elsayed and
               Alberto Barr{​​​​​​​\'{​​​​​​​o}​​​​​​​}​​​​​​​n{​​​​​​​-}​​​​​​​Cede{​​​​​​​\~{​​​​​​​n}​​​​​​​}​​​​​​​o and
               Rub\'{​​​​​​​e}​​​​​​​n M\'{​​​​​​​i}​​​​​​​guez and
               Shaden Shaar and
               Firoj Alam and
               Fatima Haouari and
               Maram Hasanain and
               Nikolay Babulkov and
               Alex Nikolov and
               Shahi, Gautam Kishore and
               Struß, Julia Maria and
               Thomas Mandl}​​​​​​​,
  title     = {​​​​​​​The {​​​​​​​CLEF}​​​​​​​-2021 {​​​​​​​CheckThat}​​​​​​​! Lab on Detecting Check-Worthy Claims, Previously Fact-Checked Claims, and Fake News}​​​​​​​,
    booktitle = {​​​​​​​Proceedings of the 43rd European Conference on Information Retrieval}​​​​​​​,
    series = {​​​​​​​ECIR~'21}​​​​​​​,
    pages = {​​​​​​​639--649}​​​​​​​,
    address   = {​​​​​​​Lucca, Italy}​​​​​​​,
    month     = {​​​​​​​March}​​​​​​​,
    year      = {​​​​​​​2021}​​​​​​​,
    url = {​​​​​​​https://link.springer.com/chapter/10.1007/978-3-030-72240-1_75}​​​​​​​​
}​​​​​​​

``` -->

## Additional Resources (Tools/Source code)
We listed the following tools/source code, which might be helpful to run the experiments.
* https://fasttext.cc/docs/en/supervised-tutorial.html
* https://huggingface.co/docs/transformers/training
* https://github.com/Tiiiger/bert_score
* https://github.com/clef2018-factchecking/clef2018-factchecking
* https://github.com/utahnlp/x-fact
* https://github.com/firojalam/COVID-19-disinformation/tree/master/bin


## Recommended reading
The following papers might be useful. We have not provided exhaustive list. But these could be a good start.<br>
[Download bibliography](bibliography.bib)

**Fact-checking**
* Nakov, Preslav, David Corney, Maram Hasanain, Firoj Alam, and Tamer Elsayed. **"Automated Fact-Checking for Assisting Human Fact-Checkers."** in IJCAI, 2021.

**COVID-19 Infodemic**
* Alam, Firoj, Shaden Shaar, Fahim Dalvi, Hassan Sajjad, Alex Nikolov, Hamdy Mubarak, Giovanni Da San Martino et al. **"Fighting the COVID-19 Infodemic: Modeling the Perspective of Journalists, Fact-Checkers, Social Media Platforms, Policy Makers, and the Society."** In Findings of the Association for Computational Linguistics: EMNLP 2021, pp. 611-649. 2021.

**Tasks papers from previous years**
* Nakov, Preslav, Giovanni Da San Martino, Tamer Elsayed, Alberto Barrón-Cedeño, Rubén Míguez, Shaden Shaar, Firoj Alam et al. **"Overview of the CLEF–2021 CheckThat! Lab on Detecting Check-Worthy Claims, Previously Fact-Checked Claims, and Fake News."** In International Conference of the Cross-Language Evaluation Forum for European Languages, pp. 264-291. Springer, Cham, 2021.
* Shaar, Shaden, Maram Hasanain, Bayan Hamdan, Zien Sheikh Ali, Fatima Haouari, Alex Nikolov, Mücahid Kutlu et al. **"Overview of the CLEF-2021 CheckThat! lab task 1 on check-worthiness estimation in tweets and political debates."** In CLEF (Working Notes). 2021.
* Shahi, Gautam Kishore, Julia Maria Struß, and Thomas Mandl. **"Overview of the CLEF-2021 CheckThat! lab task 3 on fake news detection."** Working Notes of CLEF (2021).
* Shaar, Shaden, Fatima Haouari, Watheq Mansour, Maram Hasanain, Nikolay Babulkov, Firoj Alam, Giovanni Da San Martino, Tamer Elsayed, and Preslav Nakov. **"Overview of the CLEF-2021 CheckThat! lab task 2 on detecting previously fact-checked claims in tweets and political debates."** In CLEF (Working Notes). 2021.
* Barrón-Cedeño, Alberto, Tamer Elsayed, Preslav Nakov, Giovanni Da San Martino, Maram Hasanain, Reem Suwaileh, Fatima Haouari et al. **"Overview of CheckThat! 2020: Automatic identification and verification of claims in social media."** In International Conference of the Cross-Language Evaluation Forum for European Languages, pp. 215-236. Springer, Cham, 2020.
* Shaar, Shaden, Alex Nikolov, Nikolay Babulkov, Firoj Alam, Alberto Barrón-Cedeno, Tamer Elsayed, Maram Hasanain et al. **"Overview of CheckThat! 2020 English: Automatic identification and verification of claims in social media."** In International Conference of the Cross-Language Evaluation Forum for European Languages. 2020.
* Hasanain, Maram, Fatima Haouari, Reem Suwaileh, Zien Sheikh Ali, Bayan Hamdan, Tamer Elsayed, Alberto Barrón-Cedeno, Giovanni Da San Martino, and Preslav Nakov. **"Overview of CheckThat! 2020 Arabic: Automatic identification and verification of claims in social media."** In International Conference of the Cross-Language Evaluation Forum for European Languages. 2020.
* Elsayed, Tamer, Preslav Nakov, Alberto Barrón-Cedeno, Maram Hasanain, Reem Suwaileh, Giovanni Da San Martino, and Pepa Atanasova. **"Overview of the CLEF-2019 CheckThat! Lab: automatic identification and verification of claims."** In International Conference of the Cross-Language Evaluation Forum for European Languages, pp. 301-321. Springer, Cham, 2019.
* Elsayed, Tamer, Preslav Nakov, Alberto Barrón-Cedeno, Maram Hasanain, Reem Suwaileh, Giovanni Da San Martino, and Pepa Atanasova. **"CheckThat! at CLEF 2019: Automatic identification and verification of claims."** In European Conference on Information Retrieval, pp. 309-315. Springer, Cham, 2019.
* Atanasova, Pepa, Preslav Nakov, Georgi Karadzhov, Mitra Mohtarami, and Giovanni Da San Martino. **"Overview of the CLEF-2019 CheckThat! Lab: Automatic Identification and Verification of Claims. Task 1: Check-Worthiness."** CLEF (Working Notes) 2380 (2019).
* Nakov, Preslav, Alberto Barrón-Cedeno, Tamer Elsayed, Reem Suwaileh, Lluís Màrquez, Wajdi Zaghouani, Pepa Atanasova, Spas Kyuchukov, and Giovanni Da San Martino. **"Overview of the CLEF-2018 CheckThat! Lab on automatic identification and verification of political claims."** In International conference of the cross-language evaluation forum for european languages, pp. 372-387. Springer, Cham, 2018.
* Barrón-Cedeno, Alberto, Tamer Elsayed, Reem Suwaileh, Lluís Màrquez, Pepa Atanasova, Wajdi Zaghouani, Spas Kyuchukov, Giovanni Da San Martino, and Preslav Nakov. **"Overview of the CLEF-2018 CheckThat! Lab on Automatic Identification and Verification of Political Claims. Task 2: Factuality."**   CLEF (Working Notes) 2125 (2018).
* Atanasova, Pepa, Alberto Barron-Cedeno, Tamer Elsayed, Reem Suwaileh, Wajdi Zaghouani, Spas Kyuchukov, Giovanni Da San Martino, and Preslav Nakov. **"Overview of the CLEF-2018 CheckThat! lab on automatic identification and verification of political claims. Task 1: Check-worthiness."** arXiv preprint arXiv:1808.05542 (2018).
