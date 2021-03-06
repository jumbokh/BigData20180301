# 巨量資料分析導論 上課資料

底下為概略的課綱，實際內容會隨著學生的反應調整。

(原先預定會涵蓋的容器技術，因為比較屬於 DevOps 技術而不是資料分析技術，經過考量先從課綱中往後挪，如果課程最後有足夠的時間才會再排入課綱。)

## 修課前提:

學生需了解網路基本原理、熟悉 Python 程式設計、熟悉命令列指令操作。 

## 課程目標：

讓學生瞭解巨量資料分析理論，並知悉巨量資料分析技術，預期課程結束時，學生能以 Python 相關套件實作出一個財金應用專題。

## 評分方式：

* 課堂參與及個人新知報告 (20%)
* 平時作業 (20%)
* 期中考 (30%)
* 期末報告 (30%)

## 參考書籍：

* [Sebastian Raschka, Python Machine Learning, Packt Publishing, 2015](http://bit.ly/2FM9CMN)
* [林大貴, Python+Spark 2.0+Hadoop機器學習與大數據分析實戰, 博碩出版社, 2016](http://www.books.com.tw/products/0010730134)
* [林大貴, TensorFlow+Keras深度學習人工智慧實務應用, 博碩出版社, 2017](http://www.books.com.tw/products/0010754327)

(上面書籍學校圖書館或高雄市立圖書館應該都借的到，也可查詢一下高雄雲端書庫裡面有沒有。)

## 課綱：

### Week 01. 課堂大綱解說與電腦環境設定說明

### Week 02. Python 簡介

* [Python簡介](https://github.com/victorgau/Python_Basics)
* [Homework 01](https://github.com/victorgau/BigData20180301/tree/master/Homework01) - DUE: 2018/03/16 12:00pm (中午 12 點)

### Week 03. Python 機器學習 (一)

先複習一下 Numpy, MatPlotLib，然後再簡單的說明一下機器學習的概念跟 Python 套件、模組 (e.g., scikit-learn) 的使用。從動手做激發同學們的對理論自發性的探索。

* [機器學習簡介 (投影片)](http://bit.ly/2FDEvCH)
* [Numpy, MatPlotLib, Pandas簡介](https://goo.gl/YcsKxt)
* [Scikit-Learn使用範例](https://goo.gl/BRYJz6)

### Week 04. Python 機器學習 (二)

複習 Pandas，然後繼續說明一下 supervised 跟 unsupervised machine learning 的例子。講了一點點 dimensionality reduction 跟 preprocessing。

* [GitHub - Python Machine Learning 2nd Edition](http://bit.ly/2leKZeb)
* [Homework 02](https://bit.ly/2IOLTJn)

### Week 05. Python 機器學習 (三)

繼續說明 dimensionality reduction, preprocessing, model selection 等概念。

* [關於 Overfitting](https://bit.ly/2uv4t6b)
* [什麼是 L1/L2 Regularization](https://www.youtube.com/watch?v=TmzzQoO8mr4)
* [Model Selection](https://bit.ly/2Iagwbd)
* [SVM with polynomial kernel visualization](https://www.youtube.com/watch?v=3liCbRZPrZA)
* [Data Preprocessing](https://bit.ly/2pUTkGi)
* [Model Evaluation](https://bit.ly/2E9nKtE)

### Week 06. 國定假日，不上課! (Oh Yeah~)

### Week 07. 巨量資料 (Big Data) 分析簡介

* [Big Data 簡介講義](https://bit.ly/2JFQ7ng)
* [Homework 03](https://bit.ly/2HpoGQt) - DUE: 2018/04/19 6:00pm (上課前)
* 參考：[[資料分析&機器學習] 第4.1講 : Kaggle競賽-鐵達尼號生存預測(前16%排名)](https://bit.ly/2EJubnu)

### Week 08. 雲端服務簡介

* [雲端運算簡介](https://bit.ly/2EZegl9)
* [AWS官網](https://aws.amazon.com/tw/)
* [Google Cloud官網](https://cloud.google.com/)
* [Azure官網](https://azure.microsoft.com/zh-tw/)
* [Heroku官網](https://www.heroku.com/)
* [使用 PuTTY 从 Windows 连接到 Linux 实例](https://docs.aws.amazon.com/zh_cn/AWSEC2/latest/UserGuide/putty.html)
* 參考：[文字分析Python入門](https://www.slideshare.net/xiaohuang545/python-87902078)

### Week 09. 期中複習 (公布期中考題目)

* 複習之前的上課內容
* 講一下文字處理方法
* [Midterm](https://github.com/victorgau/BigData20180301/tree/master/Midterm) - DUE: 5/6 (日) 11:59pm
* [期中考參考作法](https://youtu.be/JEO8fMb4PY8)

### Week 10. Hadoop 簡介

我們稍微說明了 Hadoop Ecosystem 及 HDFS 的架構。然後動手操作電腦中心的大數據平台，不過一開始上課時遇到一些讀寫的問題 (已修正)。之後，我們安裝了 Virtualbox，並嘗試下載最新的 Ubuntu 映像檔來使用，不過遇到版本不符的問題。所以，最後我們使用 vagrant 直接下載 Virtual Machine 的 Box 來使用。

我會請電腦中心開帳號給各位同學來練習使用 HDFS。

另外，希望各位同學嘗試使用 virtualbox 在自己的電腦上面安裝一個 Linux 作業系統來做練習。如果想要學習使用 vagrant，可以參考[這個連結](https://bit.ly/2rpdZEj)。

* [管院電腦中心大數據平台使用手冊(努力撰寫中)](https://cccm.gitbook.io/bigdata-platform-user-guide/)
* [Single Node Cluster 安裝指令](https://goo.gl/X7ZcJj)
* [Multi Node Cluster 安裝指令](https://goo.gl/Q9tCL7)
* [Hadoop+Spark安裝設定](https://ppt.cc/fphjjx)
* [Linux檔案與目錄管理指令](http://linux.vbird.org/linux_basic/redhat6.1/linux_06command.php#filesystem)
* [vagrantbox.es](http://www.vagrantbox.es/)

### Week 11. HDFS 使用練習 (一)

本次上課，我們在學校的電腦上使用 VirtualBox 安裝了 Ubuntu 16.04，並稍微說明 Linux 的使用。

每個同學都有收到一組帳號密碼，可以在管院電腦中心的 Hadoop 集群上面練習 HDFS 的使用。

另外，我們還說明如何在 AWS EC2 建立的 Instance 上面設定 notebook server，好讓 local 端可以連上雲端使用 Jupyter notebook。如果想要善用雲端的 GPU，也可以透過這樣的方式使用。

* [如何在雲端主機上面安裝 Anaconda](https://www.digitalocean.com/community/tutorials/how-to-install-the-anaconda-python-distribution-on-ubuntu-16-04)
* [Configure Jupyter Notebook on Your EC2 Instance](https://docs.aws.amazon.com/mxnet/latest/dg/setup-jupyter-configure-server.html)
* [Running a notebook server](http://jupyter-notebook.readthedocs.io/en/stable/public_server.html)

### Week 12. HDFS 使用練習 (二)

* 複習一下 Hadoop 的核心觀念。參考：[Hadoop 簡介](https://bit.ly/2Iq5ZsT)
* 簡介 Spark
* 在大數據平台上操作 spark shell，讀取 HDFS 上的文字檔。
* 說明 RDD, DataFrame, Dataset
* 說明 Transformation 及 Action APIs
* 複習 Python 的 Functional Programming 工具：lambda, map, reduce, filter

### Week 13. 深度學習簡介 (一)

* 複習 Python 的 OOP
* [簡介神經網路](https://bit.ly/2IRHOE8)
* [簡介 Keras](https://bit.ly/2ITViiw)
* [Homework 04](https://bit.ly/2sfkCZg) - DUE: 5/31 (四) 06:00pm (上課前)

### Week 14. 深度學習簡介 (二)

* 說明使用 Keras 建的 MLP 來做 Titanic 資料集的生存預測
* 說明 GD 跟 SGD。參考[此一連結](https://bit.ly/2xLATuW)。
* 說明 Python 的 yield 關鍵字跟 Generator
* 說明 online learning 跟 mini-batch
* [OOP範例](https://youtu.be/7VnWzRuGlPA)
* [Homework 05](https://bit.ly/2xhSElr) - DUE: 6/07 (四) 06:00pm (上課前)

### Week 15. Spark 機器學習 (一)

* 請務必分好組 (三人一組)，並決定期末報告的題目
* [Spark 介紹與安裝](https://goo.gl/BbHGKt)
* [Bonus 01](https://github.com/victorgau/BigData20180301/tree/master/Bonus01) - DUE: 6/14 (四) 06:00pm (上課前)

### Week 16. Spark 機器學習 (二)

* [管理學院大數據平台使用說明](https://youtu.be/p-YgqW2ySbQ)
* 期末報告摘要，DUE: 6/21 (四) 06:00pm (上課前)

### Week 17. 拾缺補遺

### Week 18. 期末報告

* 每組五分鐘，擇要報告期末報告內容。
* 每組需將期末報告做成網頁上線，內容參考[這裡](http://cm.nsysu.edu.tw/~msrc/wp/?page_id=446)。

### Week XX. 容器技術簡介

* [Get Started with Docker](https://docs.docker.com/get-started/)
* [Try Docker | Code School](https://www.codeschool.com/courses/try-docker)
* [Docker Tutorials and Labs](https://github.com/docker/labs)
* [Katacoda](https://www.katacoda.com/)

## 參考資料：

* [VirtualBox下載](https://www.virtualbox.org/wiki/Downloads)
* [Python官網](https://www.python.org/)
* [scikit-learn官網](http://scikit-learn.org/stable/)
* [kaggle官網](https://www.kaggle.com/)
* [Docker官網](https://www.docker.com/)
* [Kubernetes](https://kubernetes.io/)
* [Ansible官網](https://www.ansible.com/)
* [Vagrant官網](https://www.vagrantup.com/)
* [Hadoop官網](http://hadoop.apache.org/)
* [Spark官網](https://spark.apache.org/)

## 深度學習相關：

* [Keras 官網](https://keras.io/)
* [Theano](http://deeplearning.net/software/theano/) - 注意：Theano 已不再更新。
* [TensorFlow 官網](https://www.tensorflow.org/)
* [CNTK](https://github.com/Microsoft/CNTK)
* [PyTorch 官網](https://pytorch.org/)
* [Deep Learning 中文版](https://github.com/exacity/deeplearningbook-chinese/releases/)
* [Keras 中文說明文件](https://keras-cn.readthedocs.io/en/latest/)
* [與高中生談 Deep Learning (蔡炎龍老師)](https://bit.ly/2rT46xX)
* [Deep Learning by Andrew Ng](https://bit.ly/2rRIClO)
* [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)
* [李宏毅老師 YouTube 頻道](https://www.youtube.com/channel/UC2ggjtuuWvxrHHHiaDH1dlQ)

## 其他相關資料：

* [Unofficial Windows Binaries for Python Extension Packages](https://www.lfd.uci.edu/~gohlke/pythonlibs/)
* [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
* [鳥哥Linux私房菜](http://linux.vbird.org/)
* [現代 IT 人一定要知道的 Ansible 自動化組態技巧](https://legacy.gitbook.com/book/chusiang/automate-with-ansible/details)
* [數據分析專題（一）：引爆資料中心革命：雲端運算](https://bit.ly/2IP8cBB)
* [數據分析專題（二）：從儲存、挖掘到溝通，引領產業新面貌：大數據(Big Data)](https://bit.ly/2IBd21S)
* [數據分析專題（三）：人工智慧的黃金年代：機器學習](https://bit.ly/2IsVSHP)
* [數據分析專題（四）：機器學習的衰頹興盛：從類神經網路到淺層學習](https://bit.ly/2KFhUEb)
* [數據分析專題（五）：類神經網路的復興：深度學習簡史](https://bit.ly/2GwXk6m)
* [數據分析專題（六）：神經網路的復興：重回風口的深度學習](https://bit.ly/2k6N1wO)