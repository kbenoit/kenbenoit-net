---
id: 1459
title: Quantitative Text Analysis (TCD 2016)
date: 2016-02-04T21:48:30+00:00
author: Ken
layout: single
guid: http://www.kenbenoit.net/?p=1459
permalink: /posts/quantitative-text-analysis-tcd-2016/
categories:
  - Course-related
  - Quantitative Methods
  - Text Analysis
---
## Meeting times

5 February, 12 February, 11 March, 18 March.

## [Course Handout](http://www.kenbenoit.net/courses/tcd2016qta/QTA_TCD_syllabus_2016.pdf)

## Short Outline

The course surveys methods for systematically extracting quantitative information from political text for social scientific purposes, starting with classical content analysis and dictionary-based methods, to classification methods, and state-of-the-art scaling methods and topic models for estimating quantities from text using statistical techniques. The course lays a theoretical foundation for text analysis but mainly takes a very practical and applied approach, so that students learn how to apply these methods in actual research. The common focus across all methods is that they can be reduced to a three-step process: first, identifying texts and units of texts for analysis; second, extracting from the texts quantitatively measured features&#8212;such as coded content categories, word counts, word types, dictionary counts, or parts of speech&#8212;and converting these into a quantitative matrix; and third, using quantitative or statistical methods to analyse this matrix in order to generate inferences about the texts or their authors. The course systematically covers these methods in a logical progression, with a practical, hands-on approach where each technique will be applied using appropriate software to real texts.

## Objectives


  <div class="layout: single
    
      
        The course is also designed to cover many fundamental issues in quantitative text analysis such as inter-coder agreement, reliability, validation, accuracy, and precision. It focuses on methods of converting texts into quantitative matrixes of features, and then analysing those features using statistical methods. The course briefly covers the qualitative technique of human coding and an- notation but only for the purposes of creating a validation set for automated approaches. These automated approaches include dictionary construction and application, classification and machine learning, scaling models, and topic models. For each topic, we will systematically cover published applications and examples of these methods, from a variety of disciplinary and applied fields but focusing on political science. Lessons will consist of a mixture of theoretical grounding in content analysis approaches and techniques, with hands on analysis of real texts using content analytic and statistical software.
      
    
  


## Detailed  Course Schedule

### [Session 1: Introduction and Issues in quantitative text analysis](http://www.kenbenoit.net/courses/tcd2016qta/QTA_TCD_Day1.pdf)

This session will cover fundamentals, including the continuum from traditional (non-computer assisted) content analysis to fully automated quantitative text analysis. We will cover the conceptual foundations of content analysis and quantitative content analysis, discuss the objectives, the approach to knowledge, and the particular view of texts when performing quantitative analysis. We will also discuss issues including where to obtain textual data; formatting and working with text files; indexing and meta-data; units of analysis; and definitions of features and measures commonly extracted from texts, including stemming, and stop-words.


  <div class="layout: single
    
      <h4>
        Required Reading:
      </h4>
      
      
        - Vignette and instructions at http://github.com/kbenoit/quanteda • Grimmer and Stewart (2013)
        
        - Manning, Raghavan and Schütze (2008, 117–120)
        
        - Krippendorff (2013, Chs. 9–10)
        
        - Dunning (1993)
        
      
      
      
        <div class="layout: single
          
            <h4>
              Recommended Reading:
            </h4>
            
            
              - Krippendorff (2013, Ch. 1–2, 5, 7)
              
              - Wikipedia entry on Character encoding, http://en.wikipedia.org/wiki/Text_encoding
              
              - Browse the different text file formats at http://www.fileinfo.com/filetypes/text
              
              - Neuendorf (2002, Chs. 4–7)
              
              - Krippendorff (2013, Ch. 6)
              
              - Däubler et al. (2012)
              
            
          
        
      
    
  


**Resources:**

  * [Exercise 1: Working with Texts in quanteda](http://www.kenbenoit.net/courses/tcd2016qta/exercise1.html)
  * _[Exercise 1 solution](http://www.kenbenoit.net/courses/tcd2016qta/exercise1_answers.html)_
  * [Example code for Week 1](http://www.kenbenoit.net/courses/tcd2016qta/day1examples.R) (using [quanteda](http://github.com/kbenoit/quanteda)).

### **[Session 2: Quantitative methods for comparing texts](http://www.kenbenoit.net/courses/tcd2016qta/QTA_TCD_Day2.pdf)**


  <div class="layout: single
    
      
        Here we focus on quantitative methods for describing texts, focusing on summary measures that highlight particular characteristics of documents and allowing these to be compared. These meth- ods include characterizing texts through concordances, co-occurrences, and keywords in context; complexity and readability measures; and an in-depth discussion of text types, tokens, and equiv- alencies. We will also discuss weighting strategies for features, such as tf-idf. The emphasis will be on comparing texts, through concordances and keyword identification, dissimilarity measures, association models, and vector-space models.
      
      
      
        <div class="layout: single
          
            <h4>
              Required Reading:
            </h4>
            
            
              - Krippendorff (2013, Ch. 10)
              
              - Lowe et al. (2011)
              
              - 
                  <div class="layout: single
                    
                      Manning, Raghavan and Schütze (2008, Section 6.3)
                    
                  
                
              
            
            
            
              <div class="layout: single
                
                  <h4>
                    Recommended Reading:
                  </h4>
                  
                  
                    - 
                        <div class="layout: single
                          
                            
                              Seale, Ziebland and Charteris-Black (2006)
                            
                          
                        
                      
                    
                  
                
              
            
          
        
      
      
      
        **Resources:**
      
      
      
        - [Exercise 2: Describing and comparing texts and their features](http://www.kenbenoit.net/courses/tcd2016qta/exercise2.html)
        
        - _[Exercise 2 solution](http://www.kenbenoit.net/courses/tcd2016qta/exercise2_solution.html)_
        
        - [Example code for Week 2](http://www.kenbenoit.net/courses/tcd2016qta/day2examples.R)
        
      
    
  


### [Session 3: Automated dictionary-based approaches](http://www.kenbenoit.net/courses/tcd2016qta/QTA_TCD_Day3.pdf)


  <div class="layout: single
    
      
        Automatic dictionary-based methods involve association of pre-defined word lists with particular quantitative values assigned by the researcher for some characteristic of interest. This topic covers the design model behind dictionary construction, including guidelines for testing and refining dic- tionaries. Hand-on work will cover commonly used dictionaries such as LIWC, RID, and the Harvard IV-4, with applications. We will also review a variety of text pre-processing issues and textual data concepts such as word types, tokens, and equivalencies, including word stemming and trimming of words based on term and/or document frequency.
      
      
      
        <div class="layout: single
          
            
              <div class="layout: single
                
                  <h4>
                    Required Reading:
                  </h4>
                  
                  
                    - Neuendorf (2002, Ch. 6)
                    
                    - Laver and Garry (2000)
                    
                    - Rooduijn and Pauwels (2011)
                    
                  
                  
                  <h4>
                    Recommended Reading:
                  </h4>
                  
                  
                    - Pennebaker and Chung (2008)
                    
                    - Tausczik and Pennebaker (2010)
                    
                    - Loughran and McDonald (2011)
                    
                  
                
              
            
            
            
              **Resources:**
            
            
            
              - [Exercise 3: Applying, modifying, and creating dictionaries for the analysis of political texts.
 (](http://www.kenbenoit.net/courses/tcd2016qta/exercise3.html)and the [.Rmd source](http://www.kenbenoit.net/courses/tcd2016qta/exercise3.Rmd) for those who would like to use it as a template for their answers)
              
              - _Exercise 3 solution_
              
              - [Example code for Week 3](http://www.kenbenoit.net/courses/tcd2016qta/day3examples.R)
              
            
          
        
      
    
  



  ###  
  
  
    <div class="layout: single
      
        
          Classification methods permit the automatic classification of texts in a test set following machine learning from a training set. We will introduce machine learning methods for classifying documents, including one of the most popular classifiers, the Naive Bayes model. The topic also introduces validation and reporting methods for classifiers and discusses where these methods are applicable. Building on the Naive Bayes classifier, we introduce the “Wordscores” method of Laver, Benoit and Garry (2003) for scaling latent traits, and show the link between classification and scaling. We also cover applications of penalized regression to score and scale texts.
        
        
        
          <div class="layout: single
            
              <h4>
                Required Reading:
              </h4>
              
              
                - Manning, Raghavan and Schütze (2008, Ch. 13)
                
                - Lantz (2013, Ch. 3–4)
                
                - Evans et al. (2007)
                
                - Laver, Benoit and Garry (2003)
                
              
              
              <h4>
                Recommended Reading:
              </h4>
              
              
                - Lantz (2013, Ch. 10)
                
                - Statsoft,“NaiveBayesClassifierIntroductoryOverview,”http://www.statsoft.com/textbook/naive-bayes-classifier/.
                
                - An online article by Paul Graham on classifying spam e-mail. http://www.paulgraham. com/spam.html.
                
                - Bionicspirit.com,9Feb2012,“HowtoBuildaNaiveBayesClassifier,”http://bionicspirit. com/blog/2012/02/09/howto-build-naive-bayes-classifier.html.
                
                - Yu, Kaufmann and Diermeier (2008)
                
                - Zumel and Mount (2014, Ch. 5–6)
                
                - Benoit and Nulty (2013)
                
                - Martin and Vanberg (2007)
                
                - Benoit and Laver (2008)
                
                - Lowe (2008)
                
              
              
              
                **Resources:**
              
              
              
                - [Exercise 4: Classifying legal documents and legislative speeches.](http://www.kenbenoit.net/courses/tcd2016qta/exercise4.html)
                
                - _Exercise 4 solution_
                
                - [Example code for Week 4](http://www.kenbenoit.net/courses/tcd2016qta/day4examples.R)
                
              
            
            
            ### Final Assignment
            
            
            
              <div class="layout: single
                
                  <h4>
                    Project Guidelines
                  </h4>
                  
                  
                    The final project is a written analysis of approximately 4,000-5,000 words. The project replaces a final exam, and is designed to give you a chance to analyze a set of texts that you have chosen, reflecting (hopefully) your own research interests. This can be, and probably makes the most sense to be, textual data from something you are already studying. Which texts you choose, what question you investigate, and how you analyze the texts is your choice, but you must justify the choice.
                  
                  
                  <h4>
                    Content
                  </h4>
                  
                  
                    Your content should include the following:
                  
                  
                  <ol>
                    - A cover sheet including the title and your name.
                    
                    - An abstract page, with an abstract of no more than 200 words.
                    
                    - Introduction.
 An expanded version of your abstract, which introduces the question, states the rationale for trying to answer it, briefly describes your corpus, identifies the methods you apply to the texts, and summarizes the findings.
                    
                    - Motivation.
 Why have you chosen to analyze this topic? Is there a compelling social reason? Does it contribute to scholarship? This can include a “literature review” (but don’t overdo it).
                    
                    - Description of your corpus.
 You are free to choose any corpus you wish, of any size, although you must include a justification for the choice of texts, and acknowledge the source. You will need to document any format conversions or pre-processing steps you have applied to the texts prior to analysis. You should also present some basic summary statistics about the texts, prior to analysis.
                    
                    - Description of your methods.
 What techniques will you apply to analyze the texts? Is there a precedent (in previous scholarly literature) for applying such methods to texts similar to yours? Defend why the application of the methods is appropriate.
                    
                    - Results.
 Apply the methods, present the findings. Be sure to be explicit about any steps taken.
                    
                    - Conclusions. What conclusions on the question can we draw from the results?
                    
                  </ol>
                
              
            
            
            
              <div class="layout: single
                
                  <h4>
                    Formatting
                  </h4>
                
              
              
              <div class="layout: single
                
                  
                    There is no rigid set of guidelines, but you should use a Chicago manual of style compatible referencing system (parenthetical references rather than footnotes). Tables should be formatted rather than consisting of pasted output from a statistical package. Think of trying to look (roughly) as if you were formatting a journal article.
                  
                  
                  <h4>
                    Deadline
                  </h4>
                  
                  
                    30 April 2016, 5pm, by email to [kbenoit@tcd.ie](mailto:kbenoit@tcd.ie).
                  
                
              
            
          
        
      
    
  

