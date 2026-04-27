# Tidy-Tuesday--Water-Insecurity-
This is my TidyTuesday submission for the Water Insecurity 2023 dataset, done as part of my Program Evaluation course at Georgia State University. The dataset covers the share of U.S. households broken down by county  that lack complete indoor plumbing.
On the surface this looks like a public health or geography dataset. But I used it as a case study for causal inference and program evaluation, which is what the course is actually about. The core question I worked through is this:

Does living in a more populated county causally reduce a household's likelihood of lacking plumbing access?

That sounds simple. It isn't. Larger counties tend to be wealthier, located in different Census regions, and have more political capacity to demand infrastructure investment. All of those things independently affect plumbing access too. So a naive regression gives you a biased answer  and this project works through why that is and what to do about it, using the tools from the course.
