# Ajou-AI-Librarian
## 2022-2 Machine learning F086
### 개요
도서관에서는 도서하고자 하는 책들을 KDC(한국십진분류법)에 기반해 책의 장르를 나누고 그에 맞는 청구기호를 매겨 분류하고 있다. 책의 장르나 종류에 따라 도서관의 알맞은 위치에 책을 배치하고 있다.  
본 프로젝트는 책의 제목에 사용된 단어들은 책의 내용 및 장르를 함의하고 있음을 전제로 하고 있다. 우리는 기계학습을 통해 책의 제목과 장르간의 연관성을 찾아내고, 더 나아가 책의 제목과 아주대 도서관 책의 위치간의 상관관계가 있는지를 기존 도서들의 데이터를 통해 알아보고자 한다.  
이번 프로젝트를 통해 책을 쓰는 사람은 책 제목에 어떤 단어를 써야 사람들에게 내용을 잘 전달할 수 있을지 알 수 있게 되고, 책을 분류하는 사람 및 읽을 책을 찾는 사람은 책의 제목만으로도 어떤 내용일지 예측할 수 있게 되고, 도서관 내에서의 책의 위치도 예측할 수 있게 된다.  
또한 우리는 각 단어가 가지고 있는 사전적 의미뿐만 아니라 사전에는 등록되지 않았지만 실질적으로 사용되고 있는 단어의 새로운 의미도 기계학습을 통해 발견할 수 있을지 기대할 수 있다.  

### 구현한 것 (Using Google Colab)
아주대학교 도서관 데이터를 직접 크롤링  
Pre-Trained KoBERT를 도서관 데이터로 Fine-Tuning

![image](https://github.com/Chihiro0623/Ajou-AI-Librarian/blob/main/1.png)


[Syllabus](https://github.com/Chihiro0623/Ajou-AI-Librarian/blob/main/%EA%B8%B0%EA%B3%84%ED%95%99%EC%8A%B5.pdf)  
[Project Guide](https://github.com/Chihiro0623/Ajou-AI-Librarian/blob/main/project%20guide%202022fall.pdf)  
[Presentation](https://github.com/Chihiro0623/Ajou-AI-Librarian/blob/main/3%EC%A1%B0%20Proposal.pptx)    
[Report](https://github.com/Chihiro0623/Ajou-AI-Librarian/blob/main/3%EC%A1%B0%20Proposal.pdf)    
[Code](https://github.com/Chihiro0623/Ajou-AI-Librarian/blob/main/ml_final.ipynb)
