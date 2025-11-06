<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Communicate using Markdown

_Organize ideas and collaborate using Markdown, a lightweight language for text formatting._

</header>

<!--
  <<< Author notes: Finish >>>
  Review what we learned, ask for feedback, provide next steps.
-->

## Finish

_Congratulations friend, you've completed this course!_

<img src=https://octodex.github.com/images/welcometocat.png alt=celebrate width=300 align=right>

Here's a recap of all the tasks you've accomplished in your repository:

1. You learned about Markdown, headings, images, code examples, and task lists.
1. You created and merged a Markdown file.
1. You learned an essential GitHub skill. 🎉

### What's next?

- You can enable GitHub Pages and see your Markdown file as a website!
  1. Under your repository name at the upper right, click :gear: **Settings**.
  1. Then on the lower left, click **Pages** in the **Code and automation** section.
  1. In the **GitHub Pages** section, ensure "Deploy from a branch" is selected from the **Source** drop-down menu, and then select `main` from the **Branch** drop-down menu as your GitHub Pages publishing source.
  1. Click the **Save** button.
  1. Wait about 30 seconds then refresh the page. When you see "Your site is published at ..." you can click on the link to see your published site.
- Learn more about [Markdown](https://docs.github.com/github/writing-on-github).
- We'd love to hear what you thought of this course [in our discussion board](https://github.com/orgs/skills/discussions/categories/communicate-using-markdown)
- [Take another GitHub Skills course](https://github.com/skills).
- [Read the GitHub Getting Started docs](https://docs.github.com/get-started).
- To find projects to contribute to, check out [GitHub Explore](https://github.com/explore).

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/communicate-using-markdown) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
# El plano en R3

Un plano en el espacio queda bien determinado si se conoce su punto de paso  $P_0$  y un vector perpendicular al plano $n$ , llamado vector normal al plano.

![image.png](attachment:3c91f3eb-a63f-4abe-9f1d-f566118fb0fc:96ccea98-74cf-418f-b23c-eba21889e908.png)

### a) Ecuación Vectorial del plano

Sea  $\pi$ el plano que pasa  por  $P_0$  , y contiene a los vectores  no paralelos $\vec a$  y **$\vec b$**  , su ecuación es: 

 **Gráficamente :**

![image.png](attachment:86fb5c3d-0cf9-4037-b2b6-85acbd9d416c:image.png)

$$
\pi : P = \left\{ P_0 + r\vec{a} + s\vec{b} \;\middle|\; r, s \in \mathbb{R} \right\}
$$

**Sea:** 

$$
P = (x, y, z) \\

$$

$$
P_0 = (x_0, y_0, z_0)
$$

$$
\vec a = (a_1, a_2, a_3) 
$$

$$
\vec b= (b_1, b_2, b_3) 

$$

**Entonces :**

$$

\pi : (x, y, z) = (x_0, y_0, z_0) + r(a_1, a_2, a_3) + s(b_1, b_2, b_3)

$$

$$
\text{Donde  } r, s \in \mathbb{R}
$$

### b) Ecuaciones paramétricas del plano

En la ecuación vectorial del plano se tiene que  $\pi : (x, y, z) = (x_0, y_0, z_0) + r(a_1, a_2, a_3) + s(b_1, b_2, b_3)$
,si despejamos cada variable de la ecuación, se tiene:

 

$$
\pi :
\begin{cases}
x = x_0 + r a_1 + s b_1 \\
y = y_0 + r a_2 + s b_2 \\
z = z_0 + r a_3 + s b_3
\end{cases}
\quad 

$$

$$
\text{Donde } r, s \in \mathbb{R}

$$
