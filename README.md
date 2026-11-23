# A/Prof Kwang Cham · Scholar Dashboard

Publications, citations, venues and collaborations of A/Prof Kwang Cham (Department of Optometry and
Vision Sciences, The University of Melbourne), built with the same pipeline and design as the CIS EF
Scholar Dashboard. Data is fetched from OpenAlex (ORCID 0000-0001-6051-8520) and Google Scholar
(via SerpApi) by the GitHub Action and refreshed on the 1st of every month.

**What's on it**

- **Overview** – EF-group papers, citations, h-index, citations per year, running total, and a
  sortable table of every member.
- **Members** – one page per person: citation growth, papers per year, top venues, collaborators
  in the lab, and two "watch lists":
  - *Next h-index*: exactly which papers need how many more citations to lift the h-index by one,
    with an estimate of how long each will take at its current citation pace.
  - *Close to 10 citations*: papers that would raise the i10-index.
- **Network** – one member at a time: the selected person in the centre, everyone they have
  published with around them. Circle size = papers with that person; line width = papers the two
  ends wrote together (including between co-authors). Press **Play** to watch it grow year by year
  from their first paper; click anyone to see the papers you share. Also lists their collaborating
  institutions and co-authors.
- **Venues** – every journal and conference the lab publishes in, with citations per paper.
- **Papers** – searchable, filterable list of all lab papers.

Papers co-authored by several members are counted once in lab totals. A preprint and its
published version are merged into one paper (like Google Scholar does).
