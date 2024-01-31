# SkillsAssess2
Group 9 - Skills Assessment 2

We were working on the files. We analyze based on the PubMed database of
papers published since around 2000 which mention the biological target
in either the title or abstract.

Articles are identified by PubMed ID (PMID), which is an integer number
which uniquely identifies each paper.

The first file is a list of papers with each row representing a single
paper. Each row contains the associated information including title,
abstract, where and when the article was published and information
about the first author only.

The second file contains information about all of the authors for every
paper, with each row representing a single author. There are therefore
multiple rows for each paper, corresponding to the number of authors on
that paper.

A third file contains a count of all papers in PubMed in each year -
this includes papers which do not mention the biological target. You can
use this to estimate what proportion of papers mention your target in
a given year.

The files have been checked as far as possible, but it possible that some
entries contain unforseen problems. We worked around these by dropping a small number. To find who are the most active reaserchers, who works with whom and some additial analysis. So that it will help the organization to understand the Reaseracher who would be best fit to work as partner. 

The files columns are described below:


FILE articles.*.csv
===================

"PMID":
  Integer: the PubMed ID which uniquely identifies the paper
"Title":
  String: the title of the paper
"Abstract":
  String: the paper abstract
"ISSN":
  String: the internation standard code identifying the journal
"Journal":
  String: the title of the journal
"Location":
  String: the volumn and page numbers or article code within the journal 
"Year":
  Integer: the year of publication
"FirstAuthorForename":
  String: the first name of the first author (often missing or incomplete)
"FirstAuthorLastname":
  String: the last name of the first author
"FirstAuthorInitials":
  String: the initials of the first author (including first initial)
"FirstAuthorAffiliation":
  String: the affiliation of the first author


FILE authors.*.csv
==================

"PMID":
  Integer: the PubMed ID which uniquely identifies the paper
"AuthorN":
  Integer: the position of the author in the author list. First author = 1
"AuthorForename":
  String: the first name of the author (often missing or incomplete)
"AuthorLastname":
  String: the last name of the author
"AuthorInitials":
  String: the initials of the author (including first initial)
"AuthorAffiliation":
  String: the affiliation of the author

FILE paper_counts.csv
=====================

"Year":
  Integer: a given year
"Count":
  Integer: the number of papers published in that year included in PubMed


  Skill Assessment 2 Group 9.pptx
===================================

The presentation file group 9 had with the Business on 23th Jan.


Skill Assessment.pptx
============================

 The final presentation file group 9 had with the Business on 30th Jan.

 Skill_Assessment_2_Tabassum.ipynb
 ================================

 The visual analysis for network graph - who worked with whom by Tabassum Sultana

 Skills_Assessment_2-Gracie.ipynb
 ================================

  Who is Active - Raw data, Appended data and Bar chart visualisations - Gracie

  Skills_Assessment_2_asha.ipynb
  ================================
  The visual analysis for __________- who is active reasearchers by Asha

   Skills_assessment_2_HM.ipynb
  =================================

  The visual analysis for __________  - who is active reasearchers by Hari
