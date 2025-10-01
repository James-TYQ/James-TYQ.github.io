<!-- 
This code generates a list of publications with various details such as title, authors, conference, links, and citation information. It uses a for loop to iterate over the publications data and dynamically generates the HTML markup for each publication.

The publications are displayed in an ordered list (<ol>) with each publication represented as a list item (<li>). The list item contains a row (<div class="pub-row">) with two columns: one for the publication image and abbreviation, and the other for the publication details.

The publication image is displayed using an <img> tag with the source specified by the "link.image" variable. The abbreviation of the conference is displayed as a badge using the <abbr> tag.

The publication details such as title, authors, and conference are displayed within their respective <div> tags.

The links associated with the publication (PDF, code, project page, BibTex) are displayed as buttons using the <a> tag with the appropriate href and target attributes. The buttons are styled using CSS classes.

If there are any additional notes or other information associated with the publication, they are displayed using the <strong> and <i> tags.

If the publication has citation information available, it is displayed within a nested for loop. The citation information includes the title, year, number of citations, and a link to the "Cited By" page.

The code is written in Markdown and is intended to be used in a website or web page to display a list of publications.

-->


<h1 id="publications"></h1>

<h2 style="margin: 30px 0px 0px;">Publications <temp style="font-size:15px;">[</temp><a href="https://scholar.google.com/citations?user=DJSQsXEAAAAJ&hl=en" target="_blank" style="font-size:15px;">Google Scholar</a><temp style="font-size:15px;">]</temp><temp style="font-size:15px;">[</temp><a href="https://www.researchgate.net/scientific-contributions/Yuqi-Tang-2306085206" target="_blank" style="font-size:15px;">ResearchGate</a><temp style="font-size:15px;">]</temp></h2>

<ul class="pub-list">
  <li>
    <span class="badge">ACL 2025</span>
    <a href="https://example.com/paper.pdf">SynWorld: Virtual Scenario Synthesis for Agentic Action Knowledge Refinement</a>.<br>
    <span class="pub-authors">Runnan Fang, Xiaobin Wang, Yuan Liang, <strong>Yuqi Tang</strong>, Fei Huang, Huajun Chen.</span><br>
    <span class="pub-venue">Proceedings of ACL 2025.</span>
    <a class="pub-btn pdf" href="https://example.com/paper.pdf" target="_blank">PDF</a>
    <a class="pub-btn code" href="https://github.com/yourrepo" target="_blank">Code</a>
  </li>

  <li>
    <span class="badge">EMNLP 2024 Findings</span>
    <a href="https://example.com/llm-mechanisms.pdf">Knowledge Mechanisms in Large Language Models: A Survey and Perspective</a>.<br>
    <span class="pub-authors">Mengruo Wang, Yunzhi Yao, Ziwen Xu, <strong>Yuqi Tang</strong>, Shumin Deng, Ningyu Zhang.</span><br>
    <span class="pub-venue">Findings of EMNLP 2024.</span>
    <a class="pub-btn pdf" href="https://example.com/llm-mechanisms.pdf" target="_blank">PDF</a>
    <a class="pub-btn code" href="https://github.com/yourrepo2" target="_blank">Code</a>
  </li>

  <li>
    <span class="badge">ISWC 2024</span>
    <a href="https://example.com/instructie.pdf">InstructIE: A Bilingual Instruction-based Information Extraction Dataset</a>.<br>
    <span class="pub-authors">Honghao Gui, <strong>Yuqi Tang</strong>, Huajun Chen, Ningyu Zhang.</span><br>
    <span class="pub-venue">ISWC 2024.</span>
    <a class="pub-btn pdf" href="https://example.com/instructie.pdf" target="_blank">PDF</a>
    <a class="pub-btn code" href="https://github.com/yourrepo3" target="_blank">Code</a>
  </li>
</ul>

