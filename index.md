# CSE 232: Distributed Systems

### [Announcements](#announcements)  |  [Catalog Description](#catalog-description) | [Class Info](#class-info) | [Lecture Topics](#lecture-topics)   | [Papers for presentation](#papers-for-presentation) | [Sample Questions](#sample-questions)

**************************************************
## Announcements:

- The class will be on zoom on Thu 16, and Tue 21. Here is the zoom link  
        `removed`  

- Exam.  
   The exam will not include the following slides: 07.terminating-reliable-broadcast.pdf and 08.atomic-commit.pdf. It will include the following: 00.introduction.pdf, 01.reliable-broadcast.pdf, 02.causal-broadcast.pdf, 03.memory-regular.pdf, 04.memory-atomic.pdf, 05.Consensus.pdf, 06.total-order-broadcast.pdf, 09.bitcoin-intro.pdf, 10.byz-reliable-broadcast.pdf, and 11.byz-consensus.pdf  

- The paper schedule page:  
        `https://docs.google.com/spreadsheets/d/1BqN1j0i4DN_bStqrYNM16OCGO-UtWMRaYqbiXBxszQ8/edit#gid=0`

   The links to submit the abstracts is in the sheet.

- Recorded Lecture  
        Copy and paste the links to a browser   
        Recording 1:  
        `https://ucr.zoom.us/rec/share/MHIz_mPgPwzrzxQ_SZtwbWRHV4d_pzwc1ul5T2CfLJB1uoo9SZ7ZvNvVMHfasXM6.kVsw_nBR2jg05UGl`  
        Recording 2:  
        `https://ucr.zoom.us/rec/share/6OaVT7UG04il1YfNy3RlpPwistnL7aqUWfs_IZKn6I64N3qllwBJ9_afa-3SN0fi.qaGPG5DlHnyBf8sS`  

- There will be a midterm review session on May 17. TA will announce the location.

**************************************************
## Catalog Description

Distribution is ubiquitous in modern computing systems. For example, today's telephone systems, banking systems, global information systems, and aircraft and nuclear power plant control systems all depend critically on distributed algorithms. Robust distributed algorithms should offer reliability and security despite process failures, network disconnections, or even malicious attacks on processes. This course will introduce fundamental distributed computing problems and provides a collection of applicable algorithms. It also presents formal specification and rigorous reasoning about distributed algorithms. The course follows a modular and layered approach to the implementation of distributed abstractions. It covers reliable broadcast, causal broadcast, total-order broadcast, distributed shared memory, consensus variants including blockchain consensus, atomic commit and terminating reliable broadcast, and replicated systems. The course considers processes that are subject to crashes and also malicious attacks by non-cooperating processes.

In this course, we will have both lectures by the instructor (in the first half of the class), and presentations by students (in the second half of the class). The presenter presents a paper or related papers and leads the discussion.

**************************************************
## Class Info

### Team:
    Instructor:   
        Mohsen Lesani  
        <mlesani@ucsc.edu>  
    TA:   
        Karthik Krishnaraj Bhat  
        <kabhat@ucsc.edu>  

### Lectures:
    T/Th 3:20-4:55pm  
    Cowell 134

### Course Material at Dropbox:
    https://www.dropbox.com/scl/fo/0rsvypiv97ketway1hnh8/h?rlkey=mrpsf0b39qzcl1l4vc3k0zvrf&dl=0

### Textbook:
    Introduction to Reliable and Secure Distributed Programming  
    Christian Cachin, Rachid Guerraoui, Luís Rodrigues  
    Second Edition, Springer, 2011, XIX, 320 pages, ISBN-13: 978-3-642-15259-7  
    DOI: doi:10.1007/978-3-642-15260-3  
    http://distributedprogramming.net/index.shtml

### Office hours:
    TA:  
        Wednesday (In Person) 12pm - 1pm  
        Upper Floor/Level, Science and Engineering Library, Room 332  
        Friday (Zoom) 2.30pm - 3.30pm:  
        https://ucsc.zoom.us/j/6673631998?pwd=fvbxE7heYPstzHcJbSqlWXaetZLFxb.1  
        Passcode: yz74Ww  
        You can ask questions during the office hours, or post them on the discussion section on Canvas.  

    Instructor:  
        Please email me so that I know that you want to come to the office hours.   
        I am in most days. You can also email me and we can find a time to meet.

### Evaluation:
    One Exam (midterm from lectures in the first half of the class): 50%. May 23 in the class  
    Presentation and discussion: 50%  
    Project: extra credit

    We track attendance, and only those that attend regularly will get their grades scaled.  

    See sample questions in the following folder.  
    [Sample Questions](2.Sample_questions_and_answers/)  

**************************************************
## Lecture Topics

We may have multiple lectures on a topic.  
Please read the slides and suggested reading before the lectures.  

### 0. Introduction

    [Slides](1.Slides/00.introduction.pdf)  
    Introduction Components, Process Abstraction, Communication Abstraction, 
    Time Abstraction  
    Reading: Chapter 1 Sections 1.4, and Chapter 2 Sections 2.2, 2.4, 2.6 of the Textbook
    
### 1. Reliable Broadcast

    [Slides](1.Slides/01.reliable-broadcast.pdf)  
    Reading: Chapter 3 Sections 3.2, 3.3, 3.4, 3.9 of the Textbook

### 2. Causal Broadcast

    [Slides](1.Slides/02.causal-broadcast.pdf)  
    Reading: Chapter 3 Section 3.9 of the Textbook

### 3. Shared Memory, Regular

    [Slides](1.Slides/03.memory-regular.pdf)  
    Reading: Chapter 4 Sections 4.2 of the Textbook

### 4. Shared Memory, Atomic


    [Slides](1.Slides/04.memory-atomic.pdf)  
    Reading: Chapter 4 Sections 4.3, 4.4 of the Textbook

### 5. Consensus and Quorums

    [Slides](1.Slides/05.Consensus.pdf)  
    Reading: Chapter 2 Section 2.7, and Chapter 5 Section 5.1, 5.2, 5.3 of the Textbook

### 6. Total order Broadcast

    [Slides](1.Slides/06.total-order-broadcast.pdf)  
    Reading: Chapter 6 Section 6.1, 6.2 of the Textbook

### 7. Terminating Reliable Broadcast

    [Slides](1.Slides/07.terminating-reliable-broadcast.pdf)  
    Reading: Chapter 6 Section 6.3 of the Textbook

### 8. Atomic Commit

    [Slides](1.Slides/08.atomic-commit.pdf)  
    Reading: Chapter 6 Section 6.6 of the Textbook

### 9. View Synchronous Communication

    [Slides](1.Slides/09.view-synch-comm.pdf)  
    Reading: Chapter 6 Section 6.8 of the Textbook

### 10. Introduction to Bitcoin

    [Slides](1.Slides/09.bitcoin-intro.pdf)  
    Reading: Bitcoin A Peer-to-Peer Electronic Cash System. Nakamoto. White paper. 2008.  

### 11. Byzantine Broadcast
    
    [Slides](1.Slides/10.byz-reliable-broadcast.pdf)  
    Reading: Chapter 3 Sections 3.10, 3.11, 3.12 of the Textbook

### 12. Byzantine Consensus

    [Slides](1.Slides/11.byz-consensus.pdf)  
    Reading: Chapter 5 Section 5.6 of the Textbook

### 13. Coordination Synthesis

    [Slides](1.Slides/13.coordination-synthesis.pdf)   
    The notion of conflict, and coordination minimization by graph optimization

**************************************************
## Papers for presentation

    1. May 14  
    A comprehensive study of Convergent and Commutative Replicated Data Types.  
    M. Shapiro, N. Preguica, C. Baquero, M. Zawirski.  
    2011.  

    2. May 14  
    Coordination Avoidance in Database Systems.  
    P. Bailis, A. Fekete, M. J. Franklin, A. Ghodsi, J. M. Hellerstein, I. Stoica.  
    VLDB 2014.  

    3. May 16  
    Checking Invariant Confluence, In Whole or In Parts.  
    M. Whittaker, J. M. Hellerstein  
    VLDB 20.  

    4. May 16  
    Hamsaz: Replication Coordination Analysis and Synthesis  
    Farzin Houshmand, Mohsen Lesani  
    POPL '19 (ACM SIGPLAN Symposium on Principles of Programming Languages)  

    5. May 21 (This date has 3 presentation)  
    Efficient Numerical Error Bounding for Replicated Network Services.  
    VLDB 2001. Haifeng Yu, Amin Vahdat.  

    6. May 21  
    Hampa: Solver-aided Recency-Aware Replication  
    Xiao Li, Farzin Houshmand, Mohsen Lesani  
    CAV '20 (International Conference on Computer-Aided Verification)  

    7. May 21  
    Hamband: RDMA Replicated Data Types  
    Farzin Houshmand, Javad Saberlatibari, Mohsen Lesani  
    PLDI '22 (ACM SIGPLAN Conference on Programming Language Design 
    and Implementation)  

    May 23  
    Exam  

    8. May 28  
    Language-based Information-Flow Security.  
    A. Sabelfeld, A. C. Myers.  
    JSAC 2003  

    9. May 28  
    Secure Program Partitioning  
    S. Zdancewic, L. Zheng, N. Nystrom, A. C. Myers  
    TOCS 2002.  

    10. May 30  
    Hamraz: Resilient Partitioning and Replication  
    Xiao Li, Farzin Houshmand, Mohsen Lesani  
    S&P '22 (IEEE Symposium on Security and Privacy)  

    11. May 30  
    Federated Byzantine Quorum Systems.  
    A. G. Perez, A. Gotsman  
    OPODIS 2018.  

    12. June 4  
    Deconstructing Stellar Consensus.  
    A. G. Perez, M. A. Schett  
    OPODIS 2019.  

    13. June 4  
    Quorum Subsumption for Heterogeneous Quorum Systems  
    Xiao Li, Eric Chan, Mohsen Lesani  
    DISC '23 (The International Symposium on Distributed Computing)  

    14. June 6  
    Atomic cross-chain swaps  
    Maurice Herlihy  
    PODC 2018 (ACM symposium on principles of distributed computing. 2018)  

    15. June 6  
    Cross-Chain Transactions  
    Narges Shadab, Farzin Houshmand, Mohsen Lesani  
    ICBC '20 (IEEE International Conference on Blockchain and Cryptocurrency)  

**************************************************
## Sample Questions

    See sample questions in the following folder.  
    [Sample Questions](2.Sample_questions_and_answers/)  

**************************************************
