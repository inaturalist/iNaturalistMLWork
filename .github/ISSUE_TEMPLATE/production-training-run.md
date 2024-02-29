---
name: Production Training Run
about: This is a template for tickets that are production training runs.
title: Production Training Cycle for [VERSION]
labels: ''
assignees: ''

---

- [ ] pick a data export and bless as release version
- [ ] do same with taxon range evals
- [ ] download export and taxon range files
- [ ] delete unneeded photos from previous training run
- [ ] download validation photos
- [ ] download training photos
- [ ] make cleaned train and validation exports
- [ ] train CV model
- [ ] train geo model
- [ ] make thresholds for geomodel
- [ ] evaluate geomodel & thresholds using taxon range eval files
- [ ] evaluate models against previous release
- [ ] share models, thresholds, eval metric CSV artifacts to smilax NFS drive
- [ ] release to staging
- [ ] discuss with team approval to release
- [ ] release publicly
- [ ] write & publish announcement blog post
