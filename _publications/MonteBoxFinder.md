---
short: 'MonteBoxFinder'
title: 'MonteBoxFinder: Detecting and Filtering Primitives to Fit a Noisy Point Cloud'
collection: projects
permalink: /projects/MonteBoxFinder
thumbnail: /images/MonteBoxFinder_thumbnail.gif
date: 26-07-2021
venue: 'European Conference on Computer Vision (ECCV)'
authors: '<a href="https://michaelramamonjisoa.github.io">Michaël Ramamonjisoa</a>, <a href="https://www.tugraz.at/institute/icg/research/team-lepetit/people/sinisa-stekovic/">Sinisa Stekovic</a> and <a href="https://vincentlepetit.github.io">Vincent Lepetit</a>'
conference_short: 'ECCV 2022'
abstract: "We present MonteBoxFinder, a method that, given a noisy input point cloud, fits cuboids to the input scene. Our primary contribution is a discrete optimization algorithm that, from a dense set of initially detected cuboids, is able to efficiently filter good boxes from the noisy ones. Inspired by recent applications of MCTS to scene understanding problems, we develop a stochastic algorithm that is, by design, more efficient for our task. Indeed, the quality of a fit for a cuboid arrangement is invariant to the order in which the cuboids are added into the scene. We develop several search baselines for our problem and demonstrate, on the ScanNet dataset, that our approach is more efficient and precise. Finally, we strongly believe that our core algorithm is very general and that it could be extended to many other problems in 3D scene understanding."
bibtex: "@article{ramamonjisoa2022mbf, <br>
    Title = {MonteBoxFinder: Detecting and Filtering Primitives to Fit a Noisy Point Cloud}, <br>
    Author = {M. Ramamonjisoa, S. Stekovic and V. Lepetit}, <br>
    Journal = {European Conference on Computer Vision (ECCV)}, <br>
    Year = {2022}<br>
    }"
code: "https://github.com/MichaelRamamonjisoa/MonteBoxFinder"
pdf: "https://github.com/MichaelRamamonjisoa/MonteBoxFinder"
project_page: "https://github.com/MichaelRamamonjisoa/projects/MonteBoxFinder"
---

