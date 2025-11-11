{% from "content-macros.jinja" import flow, page, pdf, heading, alert, jsscripts  %}

<style>
  h1, h2, h3, h4, h5, h6 {
    margin-top: 32px;
    margin-bottom: 16px;
  }

 #cnt ul {
    list-style: none;
    padding-left: 0;
  }

  #cnt ul li {
    position: relative;
    padding-left: 30px;
    margin-bottom: 8px;
    margin-top: 4px;
    margin-left: 8px;
  }

  /* #cnt ul li::before {
    content: "✓";
    position: absolute;
    left: 0;
    top: 2px;
    color: #28a745;
    font-weight: bold;
    font-size: 16px;
    background: #f0f8f0;
    border-radius: 50%;
    width: 20px;
    height: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 4px;
  } */
</style>

<div id="cnt" markdown="1">
# Mathematics 

Ordinary Level

##### <i class="bi bi-folder2-open me-2"></i> Syllabus

<div style="margin-left: 30px" markdown="1">
- {{ pdf("ZIMSEC Mathematics O Level", "sample.pdf") }}
</div>

##### <i class="bi bi-journal-bookmark-fill me-2"></i> Lessons

<div style="margin-left: 32px" markdown="1">

{{ flow("Algebra", "001-linalg-recap")}}
  
-  {{ page("Summary", "test")}}
-  {{ flow("Exercise", "quiz-test")}}

[Matrices](flow:001-linalg-recap)

- [Summary](staticpage:test)
- [Exercise](flow:quiz-test)
</div>


##### {{ heading("bi-book", "Textbooks")}}

<div style="margin-left: 32px" markdown="1">
- {{ pdf("New General Mathematics Book 1", "sample.pdf") }}
- [Mathematics Today Book 3 <i class="bi bi-file-earmark-pdf text-danger"></i>](repocur:pdfs/sample.pdf) 

</div>

##### <i class="bi bi-patch-question me-2"></i> Past Exam Papers

<div style="margin-left: 32px" markdown="1">
2024

- [Paper 1 <i class="bi bi-file-earmark-pdf text-danger"></i>](repocur:pdfs/sample.pdf) </i> <i class="bi bi-dot"></i> [Marking Scheme <i class="bi bi-file-earmark-pdf text-danger"></i>](repocur:pdfs/sample.pdf) 
- [Paper 2 <i class="bi bi-file-earmark-pdf text-danger"></i>](repocur:pdfs/sample.pdf) </i> <i class="bi bi-dot"></i> [Marking Scheme <i class="bi bi-file-earmark-pdf text-danger"></i>](repocur:pdfs/sample.pdf)

2023

- [Paper 1 <i class="bi bi-file-earmark-pdf text-danger"></i>](repocur:pdfs/sample.pdf) </i> <i class="bi bi-dot"></i> [Marking Scheme <i class="bi bi-file-earmark-pdf text-danger"></i>](repocur:pdfs/sample.pdf)
</div>
</div>