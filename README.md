# School District Analysis

## Overview
Maria, the chief data scientist, has asked for help in analyzing data from across the school district that she works in. We have been informed of possible tampering and asked to redo the analysis after removing a specific subsection of the data to uphold the academic standards in our report.

## Results
The following is a comparative analysis of the data before we were informed of the academic tampering and the second analysis, done after the requested changes were made to the dataset. 
- The district summary gives us the widest look at the facts, and the first thing you may notice is the difference in total students. That is because we removed the data from about 450 students. This all taken into account, the rest of the data changed very little, indicating the inaccurate data did well in making it look reasonably close to the rest of the data. 
![district_summary_pre](https://user-images.githubusercontent.com/83182353/120045541-d8baeb80-bfd5-11eb-8b42-6b3cf83507a2.png)
![district_summary_post](https://user-images.githubusercontent.com/83182353/120045545-dce70900-bfd5-11eb-80de-feac7f997307.png)

- On the school level, we see about the same thing. First, we see the old analysis that looks about the same as the one underneath it, but all three percentages are higher before the change. The one that dropped the most between the two instances was the percentage passing both, which makes sense. 
![pre-edit_ths_info](https://user-images.githubusercontent.com/83182353/120045579-f8521400-bfd5-11eb-8542-e72b3135dbde.png)
![post-edit_ths_info](https://user-images.githubusercontent.com/83182353/120045588-fc7e3180-bfd5-11eb-9a82-c706f67b8967.png)

- Because the grades removed changed the percentages by less than one, the relative standing of Thomas High School was not affected. The schools were not that close together so such a small change in their numbers does nothing there.
![ranking_pre](https://user-images.githubusercontent.com/83182353/120046194-47e50f80-bfd7-11eb-955b-e5d20e2b3738.png)
![ranking_post](https://user-images.githubusercontent.com/83182353/120046202-4d425a00-bfd7-11eb-8604-b20fbe6a572d.png)

- Replacing the ninth graders scores, reasonable so, had arguably the largest affect on the score by grade. Although the scores for all the other grades stayed exactly the same through the change, the ninth-grade results in question were flatly replaced by NaN, as we did for all those values under the request of the district. 

![for_grades_pre](https://user-images.githubusercontent.com/83182353/120045635-1586e280-bfd6-11eb-96b5-5c202e74c760.png)
![for_grades_post](https://user-images.githubusercontent.com/83182353/120045640-1881d300-bfd6-11eb-94bc-21e55b38219e.png)

- All of the other metrics would only have the less than 1 shift, and given the rounding in most of those comparisons, the change is negligible in the comparisons based on school spending, size, and type. 
![school_spending_pre](https://user-images.githubusercontent.com/83182353/120045665-2899b280-bfd6-11eb-915d-3d74f77626b5.png)
![school_spending_post](https://user-images.githubusercontent.com/83182353/120045668-2afc0c80-bfd6-11eb-96e4-56e79b4ecd3a.png)
![size_re](https://user-images.githubusercontent.com/83182353/120046547-030da880-bfd8-11eb-937d-9d19c7e6477f.png)
![size_post](https://user-images.githubusercontent.com/83182353/120045678-2f282a00-bfd6-11eb-9cba-10fcf08e5d5f.png)
![type_pre](https://user-images.githubusercontent.com/83182353/120045685-32231a80-bfd6-11eb-86b7-edd0eb880121.png)
![type_post](https://user-images.githubusercontent.com/83182353/120045698-36e7ce80-bfd6-11eb-9d22-8fbf3efcfc76.png)


## Summary
Overall, the grades that may have been tampered with did not evoke a drastic change by being in the calculations, although they certainly did make the school in question look better than it managed to achieve. The biggest change they could have evoked was keeping a set of detrimental grades from being considered, but there is no way to fix that without going out and finding the accurate grades. We can be sure that by taking out the unreliable grades, as we did, has supplied the most accurate information that we can provide given the information that we have access to. 
