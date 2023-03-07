# Applied-Ai
Applied Ai (Papers, Articles &amp; Videos, applied in production with results)

---

Figuring out how to implement your ML project? Learn from **How other organizations have done it in past?**:
- **How** problem is framed 🔎(e.g., personalization as recsys vs. search vs. sequences)
- **What** machine learning techniques worked ✅ (and sometimes, what didn't ❌)
- **Why** it works, the science behind it with research, literature, and references 📂
- **What** real-world results were achieved (so you can better assess ROI ⏰💰📈)

---

## Content Table

1.[Practices](#practices)
2. [Failures](#failures)
3. [Data Quality](#data-quality)
4. [Data Engineering](#data-engineering)
5. [Classification](#classification)
6. [Regression](#regression)
7. [Computer Vision](#computer-vision)
8. [Natural Language Processing](#natural-language-processing)
9. [Sequence Modelling](#sequence-modelling)
10. [Optimization](#optimization)
11. [Validation and A/B Testing](#validation-and-ab-testing)

---

## Practices
1. [Practical Recommendations for Gradient-Based Training of Deep Architectures](https://arxiv.org/abs/1206.5533) ([Paper](https://arxiv.org/pdf/1206.5533.pdf)) `Yoshua Bengio`
2. [Machine Learning: The High Interest Credit Card of Technical Debt](https://research.google/pubs/pub43146/) ([Paper](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/43146.pdf)) ([Paper](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf)) `Google`
3. [Rules of Machine Learning: Best Practices for ML Engineering](https://developers.google.com/machine-learning/guides/rules-of-ml) `Google`
5. [On Challenges in Machine Learning Model Management](http://sites.computer.org/debull/A18dec/p5.pdf) `Amazon`
6. [Machine Learning in production: the Booking.com approach](https://booking.ai/https-booking-ai-machine-learning-production-3ee8fe943c70) `Booking`
7. [150 Successful Machine Learning Models: 6 Lessons Learned at Booking.com](https://www.kdd.org/kdd2019/accepted-papers/view/150-successful-machine-learning-models-6-lessons-learned-at-booking.com) ([Paper](https://dl.acm.org/doi/pdf/10.1145/3292500.3330744)) `Booking`
8. [Engineers Shouldn’t Write ETL: A Guide to Building a High Functioning Data Science Department](https://multithreaded.stitchfix.com/blog/2016/03/16/engineers-shouldnt-write-etl/) `Stitch Fix`
9. [Beware the Data Science Pin Factory: The Power of the Full-Stack Data Science Generalist](https://multithreaded.stitchfix.com/blog/2019/03/11/FullStackDS-Generalists/) `Stitch Fix`

---

## Failures
1. [160k+ High School Students Will Graduate Only If a Model Allows Them to](http://positivelysemidefinite.com/2020/06/160k-students.html) `International Baccalaureate`
2. [When It Comes to Gorillas, Google Photos Remains Blind](https://www.wired.com/story/when-it-comes-to-gorillas-google-photos-remains-blind/) `Google`
3. [An Algorithm That ‘Predicts’ Criminality Based on a Face Sparks a Furor](https://www.wired.com/story/algorithm-predicts-criminality-based-face-sparks-furor/) `Harrisburg University`

---

## Data Quality
1. [Monitoring Data Quality at Scale with Statistical Modeling](https://eng.uber.com/monitoring-data-quality-at-scale/) `Uber`
2. [An Approach to Data Quality for Netflix Personalization Systems](https://databricks.com/session_na20/an-approach-to-data-quality-for-netflix-personalization-systems) `Netflix`
3. [Automating Large-Scale Data Quality Verification](https://www.amazon.science/publications/automating-large-scale-data-quality-verification) ([Paper](https://assets.amazon.science/a6/88/ad858ee240c38c6e9dce128250c0/automating-large-scale-data-quality-verification.pdf))`Amazon`
4. [Meet Hodor — Gojek’s Upstream Data Quality Tool](https://blog.gojekengineering.com/meet-hodor-gojeks-upstream-data-quality-tool-fb877447aad1) `Gojek`
5. [Reliable and Scalable Data Ingestion at Airbnb](https://www.slideshare.net/HadoopSummit/reliable-and-scalable-data-ingestion-at-airbnb-63920989) `Airbnb`

---

## Data Engineering
1. [Zipline: Airbnb’s Machine Learning Data Management Platform](https://databricks.com/session/zipline-airbnbs-machine-learning-data-management-platform) `Airbnb`
2. [Sputnik: Airbnb’s Apache Spark Framework for Data Engineering](https://databricks.com/session_na20/sputnik-airbnbs-apache-spark-framework-for-data-engineering) `Airbnb`
3. [Introducing Feast: an open source feature store for machine learning](https://cloud.google.com/blog/products/ai-machine-learning/introducing-feast-an-open-source-feature-store-for-machine-learning) ([Code](https://github.com/feast-dev/feast))`Gojek`
4. [Feast: Bridging ML Models and Data](https://blog.gojekengineering.com/feast-bridging-ml-models-and-data-efd06b7d1644) `Gojek`
5. [Amundsen — Lyft’s Data Discovery & Metadata Engine](https://eng.lyft.com/amundsen-lyfts-data-discovery-metadata-engine-62d27254fbb9) `Lyft`
6. [Open Sourcing Amundsen: A Data Discovery And Metadata Platform](https://eng.lyft.com/open-sourcing-amundsen-a-data-discovery-and-metadata-platform-2282bb436234) ([Code](https://github.com/lyft/amundsen))`Lyft`
7. [Metacat: Making Big Data Discoverable and Meaningful at Netflix](https://netflixtechblog.com/metacat-making-big-data-discoverable-and-meaningful-at-netflix-56fb36a53520) `Netflix`
8. [How We Improved Data Discovery for Data Scientists at Spotify](https://engineering.atspotify.com/2020/02/27/how-we-improved-data-discovery-for-data-scientists-at-spotify/) `Spotify`

---

## Classification
1. [High-Precision Phrase-Based Document Classification on a Modern Scale](https://engineering.linkedin.com/research/2011/high-precision-phrase-based-document-classification-on-a-modern-scale) ([Paper](http://web.stanford.edu/~gavish/documents/phrase_based.pdf)) `LinkedIn`
2. [Chimera: Large-Scale Classification using Machine Learning, Rules, and Crowdsourcing](https://dl.acm.org/doi/10.14778/2733004.2733024) ([Paper](http://pages.cs.wisc.edu/%7Eanhai/papers/chimera-vldb14.pdf)) `WalmartLabs`
3. [Large-scale Item Categorization for e-Commerce](https://dl.acm.org/doi/10.1145/2396761.2396838) ([Paper](https://www.researchgate.net/profile/Jean_David_Ruvini/publication/262270957_Large-scale_item_categorization_for_e-commerce/links/5512dc3d0cf270fd7e33a0d5/Large-scale-item-categorization-for-e-commerce.pdf)) `DianPing`, `eBay`
4. [Large-Scale Item Categorization in e-Commerce Using Multiple Recurrent Neural Networks](https://www.kdd.org/kdd2016/subtopic/view/large-scale-item-categorization-in-e-commerce-using-multiple-recurrent-neur/) ([Paper](https://www.kdd.org/kdd2016/papers/files/adf0392-haAemb.pdf)) `NAVER`
4. [Categorizing Products at Scale](https://engineering.shopify.com/blogs/engineering/categorizing-products-at-scale) `Shopify`
5. [Learning to Diagnose with LSTM Recurrent Neural Networks](https://arxiv.org/abs/1511.03677) ([Paper](https://arxiv.org/pdf/1511.03677.pdf)) `Google`
6. [Discovering and Classifying In-app Message Intent at Airbnb](https://medium.com/airbnb-engineering/discovering-and-classifying-in-app-message-intent-at-airbnb-6a55f5400a0c) `Airbnb`
7. [How We Built the Good First Issues Feature](https://github.blog/2020-01-22-how-we-built-good-first-issues/) `GitHub`
8. [Teaching Machines to Triage Firefox Bugs](https://hacks.mozilla.org/2019/04/teaching-machines-to-triage-firefox-bugs/) `Mozilla`
9. [Testing Firefox More Efficiently with Machine Learning](https://hacks.mozilla.org/2020/07/testing-firefox-more-efficiently-with-machine-learning/) `Mozilla`
10. [Using ML to Subtype Patients Receiving Digital Mental Health Interventions](https://www.microsoft.com/en-us/research/blog/a-path-to-personalization-using-ml-to-subtype-patients-receiving-digital-mental-health-interventions/) ([Paper](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2768347)) `Microsoft`
11. [Prediction of Advertiser Churn for Google AdWords](https://research.google/pubs/pub36678/) ([Paper](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/36678.pdf)) `Google`

---

## Regression
1. [Using Machine Learning to Predict Value of Homes On Airbnb](https://medium.com/airbnb-engineering/using-machine-learning-to-predict-value-of-homes-on-airbnb-9272d3d4739d) `Airbnb`
2. [Using Machine Learning to Predict the Value of Ad Requests](https://blog.twitter.com/engineering/en_us/topics/insights/2020/using-machine-learning-to-predict-the-value-of-ad-requests.html) `Twitter`
3. [Open-Sourcing Riskquant, a Library for Quantifying Risk](https://netflixtechblog.com/open-sourcing-riskquant-a-library-for-quantifying-risk-6720cc1e4968) ([Code](https://github.com/Netflix-Skunkworks/riskquant)) `NetFlix`

---

## Computer Vision
1. [Categorizing Listing Photos at Airbnb](https://medium.com/airbnb-engineering/categorizing-listing-photos-at-airbnb-f9483f3ab7e3) `Airbnb`
2. [Amenity Detection and Beyond — New Frontiers of Computer Vision at Airbnb](https://medium.com/airbnb-engineering/amenity-detection-and-beyond-new-frontiers-of-computer-vision-at-airbnb-144a4441b72e) `Airbnb`
3. [Powered by AI: Advancing product understanding and building new shopping experiences](https://ai.facebook.com/blog/powered-by-ai-advancing-product-understanding-and-building-new-shopping-experiences/) `Facebook`
4. [Creating a Modern OCR Pipeline Using Computer Vision and Deep Learning](https://dropbox.tech/machine-learning/creating-a-modern-ocr-pipeline-using-computer-vision-and-deep-learning) `Dropbox`
5. [How we Improved Computer Vision Metrics by More Than 5% Only by Cleaning Labelling Errors](https://deepomatic.com/en/how-we-improved-computer-vision-metrics-by-more-than-5-percent-only-by-cleaning-labelling-errors/) `Deepomatic`
6. [A Neural Weather Model for Eight-Hour Precipitation Forecasting](https://ai.googleblog.com/2020/03/a-neural-weather-model-for-eight-hour.html) ([Paper](https://arxiv.org/pdf/2003.12140.pdf)) `Google`
7. [Machine Learning-based Damage Assessment for Disaster Relief](https://ai.googleblog.com/2020/06/machine-learning-based-damage.html) ([Paper](https://arxiv.org/pdf/1910.06444.pdf)) `Google`
8. [RepNet: Counting Repetitions in Videos](https://ai.googleblog.com/2020/06/repnet-counting-repetitions-in-videos.html) ([Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Dwibedi_Counting_Out_Time_Class_Agnostic_Video_Repetition_Counting_in_the_CVPR_2020_paper.pdf)) `Google`
9. [Converting Text to Images for Product Discovery](https://www.amazon.science/blog/converting-text-to-images-for-product-discovery) ([Paper](https://assets.amazon.science/4c/76/5830542547b7a11089ce3af943b4/scipub-972.pdf)) `Amazon`
10. [How Disney uses PyTorch for Animated Character Recognition](https://medium.com/pytorch/how-disney-uses-pytorch-for-animated-character-recognition-a1722a182627) `Disney`
12. [Image Captioning as an Assistive Technology](https://www.ibm.com/blogs/research/2020/07/image-captioning-assistive-technology/) ([Video](https://ivc.ischool.utexas.edu/~yz9244/VizWiz_workshop/videos/MMTeam-oral.mp4)) `IBM`

---

## Natural Language Processing
1. [Abusive Language Detection in Online User Content](https://dl.acm.org/doi/10.1145/2872427.2883062) ([Paper](http://www.yichang-cs.com/yahoo/WWW16_Abusivedetection.pdf)) `Yahoo`
2. [How Natural Language Processing Helps LinkedIn Members Get Support Easily](https://engineering.linkedin.com/blog/2019/04/how-natural-language-processing-help-support) `LinkedIn`
3. [Building Smart Replies for Member Messages](https://engineering.linkedin.com/blog/2017/10/building-smart-replies-for-member-messages) `LinkedIn`
4. [Smart Reply: Automated Response Suggestion for Email](https://research.google/pubs/pub45189/) ([Paper](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45189.pdf)) `Google`
5. [SmartReply for YouTube Creators](https://ai.googleblog.com/2020/07/smartreply-for-youtube-creators.html) `Google`
6. [Using Neural Networks to Find Answers in Tables](https://ai.googleblog.com/2020/04/using-neural-networks-to-find-answers.html) ([Paper](https://arxiv.org/pdf/2004.02349.pdf)) `Google`
7. [A Scalable Approach to Reducing Gender Bias in Google Translate](https://ai.googleblog.com/2020/04/a-scalable-approach-to-reducing-gender.html) `Google`
8. [Assistive AI Makes Replying Easier](https://www.microsoft.com/en-us/research/group/msai/articles/assistive-ai-makes-replying-easier-2/) `Microsoft`
9. [AI Advances to Better Detect Hate Speech](https://ai.facebook.com/blog/ai-advances-to-better-detect-hate-speech/) `Facebook`
10. [A State-of-the-Art Open Source Chatbot](https://ai.facebook.com/blog/state-of-the-art-open-source-chatbot) ([Paper](https://arxiv.org/pdf/2004.13637.pdf)) `Facebook`
11. [A Highly Efficient, Real-Time Text-to-Speech System Deployed on CPUs](https://ai.facebook.com/blog/a-highly-efficient-real-time-text-to-speech-system-deployed-on-cpus/) `Facebook`
12. [Goal-Oriented End-to-End Conversational Models with Profile Features in a Real-World Setting](https://www.amazon.science/publications/goal-oriented-end-to-end-chatbots-with-profile-features-in-a-real-world-setting) ([Paper](https://assets.amazon.science/47/03/e0d14dc34d3eb6e0d4ec282067bd/goal-oriented-end-to-end-chatbots-with-profile-features-in-a-real-world-setting.pdf)) `Amazon`
13. [How Gojek Uses NLP to Name Pickup Locations at Scale](https://blog.gojekengineering.com/how-gojek-uses-nlp-to-name-pickup-locations-at-scale-ffdb249d1433) `GoJek`
14. [Give Me Jeans not Shoes: How BERT Helps Us Deliver What Clients Want](https://multithreaded.stitchfix.com/blog/2019/07/15/give-me-jeans/) `Stitch Fix`
15. [The State-of-the-art Open-Domain Chatbot in Chinese and English](http://research.baidu.com/Blog/index-view?id=142) ([Paper](https://arxiv.org/pdf/2006.16779.pdf)) `Baidu`
16. [Deep Learning to Translate Between Programming Languages](https://ai.facebook.com/blog/deep-learning-to-translate-between-programming-languages/) ([Paper](https://arxiv.org/abs/2006.03511)) `Facebook`
17. [PEGASUS: A State-of-the-Art Model for Abstractive Text Summarization](https://ai.googleblog.com/2020/06/pegasus-state-of-art-model-for.html) ([Paper](https://arxiv.org/pdf/1912.08777.pdf)) ([Code](https://github.com/google-research/pegasus)) `Google`

---

## Sequence Modelling
1. [Recommending Complementary Products in E-Commerce Push Notifications with Mixture Models](https://arxiv.org/abs/1707.08113) ([Paper](https://arxiv.org/pdf/1707.08113.pdf)) `Alibaba`
2. [Practice on Long Sequential User Behavior Modeling for Click-Through Rate Prediction](https://arxiv.org/abs/1905.09248) ([Paper](https://arxiv.org/pdf/1905.09248.pdf))`Alibaba`
3. [Search-based User Interest Modeling with Lifelong Sequential Behavior Data for CTR Prediction](https://arxiv.org/abs/2006.05639) ([Paper](https://arxiv.org/pdf/2006.05639.pdf)) `Alibaba`
4. [Learning to Diagnose with LSTM Recurrent Neural Networks](https://arxiv.org/abs/1511.03677) ([Paper](https://arxiv.org/pdf/1511.03677.pdf)) `Google`
5. [Deep Learning for Understanding Consumer Histories](https://engineering.zalando.com/posts/2016/10/deep-learning-for-understanding-consumer-histories.html) ([Paper](https://doogkong.github.io/2017/papers/paper2.pdf)) `Zalando`
6. [Continual Prediction of Notification Attendance with Classical and Deep Network Approaches](https://arxiv.org/abs/1712.07120) ([Paper](https://arxiv.org/pdf/1712.07120.pdf)) `Telefonica`
7. [Using Recurrent Neural Network Models for Early Detection of Heart Failure Onset](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5391725/) ([Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5391725/pdf/ocw112.pdf)) `Sutter Health`
8. [Doctor AI: Predicting Clinical Events via Recurrent Neural Networks](https://arxiv.org/abs/1511.05942) ([Paper](https://arxiv.org/pdf/1511.05942.pdf)) `Sutter Health`

---

## Optimization
1. [How Trip Inferences and Machine Learning Optimize Delivery Times on Uber Eats](https://eng.uber.com/uber-eats-trip-optimization/) `Uber`
2. [Next-Generation Optimization for Dasher Dispatch at DoorDash](https://doordash.engineering/2020/02/28/next-generation-optimization-for-dasher-dispatch-at-doordash/) `DoorDash`
3. [Matchmaking in Lyft Line (Part 1)](https://eng.lyft.com/matchmaking-in-lyft-line-9c2635fe62c4) [(Part 2)](https://eng.lyft.com/matchmaking-in-lyft-line-691a1a32a008) [(Part 3)](https://eng.lyft.com/matchmaking-in-lyft-line-part-3-d8f9497c0e51) `Lyft`
4. [The Data and Science behind GrabShare Carpooling](https://ieeexplore.ieee.org/document/8259801) (**PAPER NEEDED**) `Grab`

---

## Validation and A/B Testing
1. [The Reusable Holdout: Preserving Validity in Adaptive Data Analysis](https://ai.googleblog.com/2015/08/the-reusable-holdout-preserving.html) ([Paper](https://science.sciencemag.org/content/sci/349/6248/636.full.pdf)) `Google`
3. [Detecting Interference: An A/B Test of A/B Tests](https://engineering.linkedin.com/blog/2019/06/detecting-interference--an-a-b-test-of-a-b-tests) `LinkedIn`
4. [Building Inclusive Products Through A/B Testing](https://engineering.linkedin.com/blog/2020/building-inclusive-products-through-a-b-testing) ([Paper](https://arxiv.org/pdf/2002.05819.pdf)) `LinkedIn`
5. [Experimenting to Solve Cramming](https://blog.twitter.com/engineering/en_us/topics/insights/2017/Experimenting-To-Solve-Cramming.html) `Twitter`
6. [Announcing a New Framework for Designing Optimal Experiments with Pyro](https://eng.uber.com/oed-pyro-release/) ([Paper](https://papers.nips.cc/paper/9553-variational-bayesian-optimal-experimental-design.pdf)) ([Paper](https://arxiv.org/pdf/1911.00294.pdf)) `Uber`
7. [Enabling 10x More Experiments with Traveloka Experiment Platform](https://medium.com/traveloka-engineering/enabling-10x-more-experiments-with-traveloka-experiment-platform-8cea13e952c) `Traveloka`
8. [Large scale experimentation at StitchFix](https://multithreaded.stitchfix.com/blog/2020/07/07/large-scale-experimentation/) ([Paper](http://proceedings.mlr.press/v89/schmit19a/schmit19a.pdf)) `Stitch Fix`
9. [Modeling Conversion Rates and Saving Millions Using Kaplan-Meier and Gamma Distributions](https://better.engineering/modeling-conversion-rates-and-saving-millions-of-dollars-using-kaplan-meier-and-gamma-distributions/) ([Code](https://github.com/better/convoys)) `Better`

