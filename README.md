# HugoCunhaCV.github.io

Personal site for Hugo Cunha. CV, projects, and TryHackMe SOC Level 1 writeups.

Live at: https://hugocunhacv.github.io

## Structure

```
.
├── index.html                          Home
├── projects.html                       Projects (ThePassLab + planned)
├── writeups.html                       Writeups tree (TryHackMe)
├── cv.html                             Full CV + cover letters
├── style.css                           Shared stylesheet
├── headshot.jpg                        Profile picture
├── Hugo_Cunha_CV_2026.pdf
├── Hugo_Cunha_Cover_Letter_EN.pdf
├── Hugo_Cunha_Carta_Apresentacao.pdf
├── README.md
└── thm/
    ├── 01-blue-team-introduction/      (4 rooms)
    ├── 02-soc-team-internals/          (4 rooms)
    ├── 03-core-soc-solutions/          (5 rooms)
    ├── 04-cyber-defence-frameworks/    (6 rooms)
    ├── 05-phishing-analysis/           (7 rooms)
    └── 06-network-traffic-analysis/    (5 rooms)
```

Single repository, 40 files. All writeups live at `/thm/<module>/<room>.html`. The only external link is ThePassLab, which has its own dedicated repository.

## Deploy on GitHub Pages

1. Create a public repository named exactly `HugoCunhaCV.github.io` under the `HugoCunhaCV` account.
2. Upload every file and folder in this directory to the repository root, preserving the `thm/` folder structure.
3. Settings → Pages → Source: main branch, root folder.
4. The site goes live at `https://hugocunhacv.github.io` within a couple of minutes.

## Updating a writeup

Each room is a standalone HTML file under `thm/<module>/<room>.html`.

1. Edit the room file in the GitHub web editor (pencil icon) or locally.
2. Replace the italic grey placeholder text inside each `<div class="block tba">` block.
3. Remove the `tba` class once you've added real content (drops the striped background).
4. Add as many `<div class="task">` blocks under "walkthrough" as the room has tasks.
5. Once finalised, change the META status from "Writeup in progress" to "Complete" and delete the amber WRITEUP COMING SOON banner.

## Contact

[LinkedIn](https://www.linkedin.com/in/cunhahugo) · eng.hugocunha@gmail.com
