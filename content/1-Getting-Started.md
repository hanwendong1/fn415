---
title: Getting Started
nav: true
--- 

When conducting college-level research, there is a general process to follow:

{% capture text %}

1. Select topic
2. Use Boolean logic to expand or narrow key concepts or keywords
3. Select a database
4. Evaluate and revise the search strategy
5. Choose items and find full-text online or in print

{% endcapture %}

{% include card.md text=text header="Research Process" %}

Ideally, you chose a topic you were somewhat familiar with or interested in researching. To get more information and ideas on the topic you selected, use <a href="https://www.google.com/" target="_blank" rel="noopener">Google</a>, or <a href="https://www.wikipedia.org/" target="_blank" rel="noopener">Wikipedia</a>. Note that you can't cite a Wikipedia article or most websites from a Google search. You can, however, find some keywords that you can use or some peer-reviewed literature (references at the bottom of a Wikipedia article, for instance) and other linked sources to gray literature and scholarly literature.

What are the differences among popular, scholarly, and gray literature? Below are the characteristics of each source that can help you differentiate from others:
* Popular/General Interest (news, media, magazines)
    + Shorter articles with broad overviews of topics
    + Published to inform, entertain, or persuade
    + Possibly a “suggested reading” list, usually no bibliography
    + Authors are often journalists or staff writers; No credentials are provided
    + Articles are not evaluated by experts in the field, but by editors on staff
* Scholarly Journals (peer-reviewed or refereed)
    + Longer articles providing in-depth analysis of topics
    + Publish original research in a field
    + Bibliography provided to document research
    + Authors are usually experts or specialists in the field; Names and credentials are always provided
    + Articles are reviewed and evaluated by experts in the field (refereed)
* Gray Literature (bulletins, trade journals, science communications, gov’t reports)
    + Long or short, depending on the intended audience
    + Published through the government, organizations, institutes, and interest groups; Often original research
    + Bibliographies usually provided
    + Authors are usually experts or specialists in the field; Names and credentials are always provided
    + Articles are often written by experts but are mostly not peer-reviewed. In some cases, e.g., federal agencies, they may have internal peer-review
 
Now let’s talk about Boolean logic. 

## Boolean Logic

Boolean logic uses Boolean operators (such as `AND`, `OR`, `NOT`) to narrow, expand, or define a search, and is applicable to conducting searches in library catalog and most databases. Writing out your search terms using Boolean operators by connecting pieces of information and coming up with synonyms is a good exercise as it can show wanted results and filter out unrelated results. Below are some of the advanced searching techniques including Boolean operators you can use:

<html>
   <head>
      <style>
         table {width: 100%;}
         table, td, th {
            border-collapse: collapse;
            padding: 8px;
            border-bottom: 1px solid #ddd;
         
         th {            
            style="text-align:Center"
            border: 1px solid black;
            padding-top: 12px;
            padding-bottom: 12px;
            background-color: #060400;
            color: white;
            }
      </style>
   </head>
   <body>
      <table>
         <tr>
            <th style="background-color: #060400; color: #f1b300; text-align:Center">Boolean Operator</th>
            <th style="background-color: #060400; color: #f1b300; text-align:Center">Explanation</th>
            <th style="background-color: #060400; color: #f1b300; text-align:Center">Example</th>
         </tr>
         <tr>
            <th style="text-align:Center">AND</th>
            <td style="text-align:Left">Each result contains all search terms</td>
            <td style="text-align:Left">Zinc AND cold</td>
         </tr>
         <tr>
            <th style="text-align:Center">OR</th>
            <td style="text-align:Left">Each result contains at least one search term</td>
            <td style="text-align:Left">energy OR fatique OR weakness</td>
         </tr>
         <tr>
            <th style="text-align:Center">" "</th>
            <td style="text-align:Left">Results must include search terms in the defined order</td>
            <td style="text-align:Left">"iron deficiency anemia"</td>
         </tr>
          <tr>
            <th style="text-align:Center">NOT</th>
            <td style="text-align:Left">Results do not contain the specified terms</td>
            <td style="text-align:Left">B6 NOT B12</td>
         </tr>
         <tr>
            <th style="text-align:Center">*</th>
            <td style="text-align:Left">Results can include search terms with different endings of the root word</td>
            <td style="text-align:Left">depress* [for depression, depressive, depressed, etc.]</td>
         </tr>         
         <tr>
            <th style="text-align:Center">?</th>
            <td style="text-align:Left">Results include words with alternative spellings</td>
            <td style="text-align:Left">an?emia [for anemia or anaemia]</td>
         </tr>
          <tr>
            <th style="text-align:Center">( )</th>
            <td style="text-align:Left">Results include the phrase with the order of relationships organized</td>
            <td style="text-align:Left">"iron deficiency anemia" AND (growth OR development)</td>
         </tr>
      </table>
   </body>
   <p>
   </p>
</html>

{% capture text %}You can check out [this guide](https://libguides.uidaho.edu/boolean){:target="_blank" rel="noopener"} to learn more about Boolean logic. Also note that all databases are different. You can check the help section of your chosen database to see what boolean operators are accepted and what symbols they used.
{% endcapture %}
{% include alert.md text=text color="warning" %}
