# Skill Diary Database Vöcklabruck
## Informational Stuff
The trainers of CODERS.BAY decided to let you write a documentation of what you have learned. 

Please keep this as your diary and write a short summary with code snippets and some theoretical topics daily in the last half an hour of the day.

Just to let you know this will be your personal reference book. 

You are going to have three GIT Repositories where you document your progress of the course.

In this Repository we are gonna collect all information of the database classes. 

I'm going to give you all reviews in the form of issues every week, where I'm going to review your documentary by the following criteria:
- code quality
- quality of content 
- totality of your documentation.

As it is a personal documentation the styling and structure is up to your personal preferences.

## Markdown Cheatsheet
### Headlines

<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      # TEXT
    </td>
    <td>
      <h1> This is a H1 </h1>
    </td>
  </tr>
  <tr>
    <td> 
      ## TEXT
    </td>
    <td>
      <h2> This is a H2 </h2>
    </td>
  </tr>
  <tr>
    <td> 
      ### TEXT
    </td>
    <td>
      <h3> This is a H3 </h3>
    </td>
  </tr>
  <tr>
    <td> 
      #### TEXT
    </td>
    <td>
      <h4> This is an H4 </h4>
    </td>
  </tr>
  <tr>
    <td> 
      ##### TEXT
    </td>
    <td>
      <h5> This is an H5 </h5>
    </td>
  </tr>
  <tr>
    <td> 
      ###### TEXT
    </td>
    <td>
      <h6> This is an H6 </h6>
    </td>
  </tr>
</table>

### Emphasis
#### Italic
<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      *This text will be italic*
    </td>
    <td>
      <i> This text will be italic </i>
    </td>
  </tr>
  <tr>
    <td> 
       _This text will be italic too_
    </td>
    <td>
      <i> This text will be italic too</i>
    </td>
  </tr>
</table>

#### Bold
<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      *This text will be bold*
    </td>
    <td>
      <b> This text will be bold </b>
    </td>
  </tr>
  <tr>
    <td> 
       __This text will be bold too__
    </td>
    <td>
      <b> This text will be bold too</b>
    </td>
  </tr>
</table>

### Lists
#### Unordered
<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      * Item 1 <br/>
      * Item 2 <br/>
      TAB * Item 2a <br/>
      TAB * Item 2b <br/>
    </td>
    <td>
      <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <ul>
          <li>Item 2a</li>
          <li>Item 2b</li>
        </ul>
      </ul>
    </td>
  </tr>
</table>

#### Ordered

<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      1. Item 1 <br/>
      2. Item 2 <br/>
    </td>
    <td>
        <ol>
        <li>Item 1</li>
        <li>Item 2</li>
      </ol>
    </td>
  </tr>
</table>

### Images
<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      ![GitHub Logo](/images/logo.png)<br/>
      Format: ![Alt Text](url)
    </td>
    <td>
      Displays the image in folder images which is called logo.png
    </td>
  </tr>
</table>

### Links


<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      ![GitHub](https://www.github.com)<br/>
      Format: ![Alt Text](url)
    </td>
    <td>
      <a href = "https://www.github.com">GitHub</a>
    </td>
  </tr>
</table>

### Backslash Escape
If you need the characters, which are already used as special characters in Markdown you can use them if you put an \\ before the character. For example you have to write ```\*``` to use a \*

### Using code in Markdown
Markdown coverts text with four leading spaces into a code block; with GFM you can wrap your code with \`\`\` to create a code block without the leading spaces. Add an optional language identifier and your code will get syntax highlighting.



![CodeSnippet](/Codesnippet.png)

### Tables
You can create tables by assembling a list of words and dividing them with hyphens \- (for the first row), and then separating each column with a pipe \| 
<table>
  <tr>
    <td> 
      Markdown Syntax 
    </td>
    <td>
      How it looks
    </td>
  </tr>
   <tr>
    <td> 
      First Header | Second Header<br/>
      ------------ | ------------- <br/>
      Content cell 1 | Content cell 2 <br/>
      Content column 1 | Content column 2
    </td>
    <td>
      <table>
        <thead>
            <td> 
               First Header
            </td>
            <td>
              Second Header
            </td>
       </thead>
       <tbody>
         <tr>
          <td> 
            Content cell 1
          </td>
          <td>
            Content cell 2
          </td>
        </tr>
         <tr>
          <td> 
            Content column 1
          </td>
          <td>
            Content column 2
          </td>
        </tr>
       </tbody>  
      </table>
    </td>
  </tr>
</table>

## 11th June 2021
Today I learned two topics:

1. The First Steps into the world of databases.
2. What is an ER - Model and how do you create it.

__Why Databases?__

* Security against losses
* Access to data of multiple users
* Structured deposit of the data

__The 9 Cood's Requirements__

1. Integration
2. Operation
3. Data Dictionary
4. User View
5. Integrity Assurance
6. Access Control
7. Transaction
8. Synchronisation
9. Data Backup

__Data Modeling__

Cutout -> Conceptual scheme  -> Logical scheme -> Query & Manipulation

__Entity Relationship Model (ER - Model)__

* Models entities and the relationships between them
  1. Entity
    * Object about which information is to be stored (Ex.: lecture, professor, exam)
  2. Relationship
    * Relationship between entities (Ex: Professor reads lecture)
  3. Attribute
    * Property of entities or relations (name, title,...)
  4. Values
    * Primitive data elements that can be created directly
    * Values are described by data types
  5. Data types
    * Given default data types (Ex: int, varchar, date)

__Key__

* The values of the key attributes uniquely identify entities
* If there are several key candidates, a primary key must be choosen (underline in the model)

*End of Diary*
