---
# Display name
title: Peter Yatsyshin

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: '' #Professor of Artificial Intelligence

# Organizations/Affiliations to show in About widget
organizations:
  - name: Imperial College London
    url: https://www.imperial.ac.uk/complex-multiscale-systems/our-group/dr-peter-yatsyshin/
  - name: The Alan Turing Institute
    url: https://www.turing.ac.uk/people/researchers/peter-yatsyshin 


# Short bio (displayed in user profile at end of posts)
bio: My research interests include distributed robotics, mobile computing and programmable matter.

# Interests to show in About widget
interests:
  - Artificial Intelligence
  - Computational Linguistics
  - Information Retrieval

# Education to show in About widget
education:
  courses:
    - course: PhD in Artificial Intelligence
      institution: Stanford University
      year: 2012
    - course: MEng in Artificial Intelligence
      institution: Massachusetts Institute of Technology
      year: 2009
    - course: BSc in Artificial Intelligence
      institution: Massachusetts Institute of Technology
      year: 2008

# Social/Academic Networking
# For available icons, see: https://wowchemy.com/docs/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: 'mailto:p.yatsyshin@icloud.com'
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/GeorgeCushen
  - icon: graduation-cap # Alternatively, use `google-scholar` icon from `ai` icon pack
    icon_pack: fas
    link: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
  - icon: github
    icon_pack: fab
    link: https://github.com/gcushen
  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/

# Link to a PDF of your resume/CV.
# To use: copy your resume to `static/uploads/resume.pdf`, enable `ai` icons in `params.toml`,
# and uncomment the lines below.
  # - icon: cv
  #   icon_pack: ai
  #   link: uploads/CV_academic.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ''

# Highlight the author in author lists? (true/false)
highlight_name: true
---



```latex
\documentclass{article}

\begin{document}
Primer documento. Este es un ejemplo simple, sin incluir ningún parámetro (opción) o paquete extra.
\end{document}
```

```python
import numpy as np

for i in range(10):
  print(i)
```

```
import numpy as np

for i in range(10):
  print(i)
```

{{< highlight python >}}
import numpy as np

for i in range(10):
  print(i)
{{< /highlight >}}


{{< highlight html >}}
<section id="main">
  <div>
    <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}

without python keyword
```
# Example of code highlighting
input_string_var = input("Enter some data: ")
print("You entered: {}".format(input_string_var))
```

with python keyword
```python
# Example of code highlighting
input_string_var = input("Enter some data: ")
print("You entered: {}".format(input_string_var))
```

$$E=mc^2$$

Nelson Bighetti is a professor of artificial intelligence at the Stanford AI Lab. His research interests include distributed robotics, mobile computing and programmable matter. He leads the Robotic Neurobiology group, which develops self-reconfiguring robots, systems of self-organizing robots, and mobile sensor networks.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.

<table class="table table-borderless">
  <thead>
    <tr>
      <th scope="col">{{< icon name="download" pack="fas" >}} {{< staticref "uploads/CV_business.pdf" "newtab" >}}Business CV   {{< /staticref >}}</th>
      <th scope="col">{{< icon name="download" pack="fas" >}} {{< staticref "uploads/CV_academic.pdf" "newtab" >}}Academic CV   {{< /staticref >}}</th>
      <th scope="col">{{< icon name="download" pack="fas" >}} {{< staticref "uploads/CV_teaching.pdf" "newtab" >}}Teaching Statement{{< /staticref >}}</th>
    </tr>
  </thead>
</table>

<!-- <table class="table table-borderless">
  <thead>
    <tr>
      <th scope="col">{{< icon name="download" pack="fas" style="color:red;" >}} Download:</th>
      <th scope="col">{{< staticref "uploads/CV_business.pdf" "newtab" >}}Business CV   {{< /staticref >}}</th>
      <th scope="col">{{< staticref "uploads/CV_academic.pdf" "newtab" >}}Academic CV   {{< /staticref >}}</th>
      <th scope="col">{{< staticref "uploads/CV_teaching.pdf" "newtab" >}}Teaching Statement{{< /staticref >}}</th>
    </tr>
  </thead>
</table> -->
