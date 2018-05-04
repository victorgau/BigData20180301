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
* 參考：[文字分析Python入門](https://www.slideshare.net/xiaohuang545/python-87902078)

### Week 09. 期中複習 (公布期中考題目)

* 複習之前的上課內容
* 講一下文字處理方法
* [Midterm](https://github.com/victorgau/BigData20180301/tree/master/Midterm) - DUE: 5/6 (日) 11:59pm

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

### Week 11. Hadoop 使用教學 (一)

### Week 12. Hadoop 使用教學 (二)

### Week 13. Spark 環境建置說明

* [Spark 介紹與安裝](https://goo.gl/BbHGKt)

### Week 14. Spark 使用教學

### Week 15. Spark 機器學習 (一)

### Week 16. Spark 機器學習 (二)

### Week 17. Spark 機器學習 (三)

### Week 18. 期末報告

### Week XX. 深度學習簡介

* [Deep Learning 中文版](https://github.com/exacity/deeplearningbook-chinese/releases/)

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

## 相關資料：

* [Unofficial Windows Binaries for Python Extension Packages](https://www.lfd.uci.edu/~gohlke/pythonlibs/)
* [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
* [鳥哥Linux私房菜](http://linux.vbird.org/)