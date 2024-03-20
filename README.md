# link_analysis
Discussions link analysis

The dataset comprises 10 CSV files, each containing information about the link references extracted in 2022 for the following repositories:

dotnet/csharplang
gatsbyjs/gatsby
laravel/framework
livewire/livewire
prisma/prisma
react-hook-form/react-hook-form
tanStack/react-table
tailwindlabs/tailwindcss
vercel/vercel
vercel/next.js

Each CSV file contains data about analyzed repositories in a study. In these files, each row represents a reference link, and the columns are structured to include 'discussion_id', 'link', 'link_place', and 'link_type'. The 'discussion_id' is the unique identifier for discussion threads related to the repository. The 'link' column contains URLs extracted from the discussion threads of the repository. 'Link_place' specifies the location (main body or comments) where the link can be found within the discussion thread. 'Link_type' categorizes the nature of the link, according to Figure 3 of the paper.
