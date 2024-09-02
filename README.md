# Template Repository for Open source software
An example repository structure for open source software publishing. 

Check out GNU's description of [Free Software](https://www.gnu.org/philosophy/free-sw.html) to understand the core principles of free software. 

1. Release custom codes used in manuscripts as repositories
2. Add clear code availability statements in manuscripts.
3. If your software is complex with specific dependencies, consider creating a [Docker](https://docs.docker.com/get-started/docker-overview/) to allow the user to easily run the software. 

## Points to note
* Use Git
* Ask you collborators to review your code - increases the likelihood of catching errors
* Keep sensitive data such as credentials secure and separate from source code.

## How to use this template
Please follow the guidelines here to create a repository using this template:
[Creating from a template repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)
## Licenses
Due to the lack of specific terminology about the code distribution Creative Commons [recommends against using Creative Commons licenses for software](https://creativecommons.org/faq/#can-i-apply-a-creative-commons-license-to-software) and rather use already available open source software licenses. MIT License and GNU GPL v3.0 are the two most commonly used opensource software licenses. The major difference between MIT and GNU GPL is that the former is a simple license that allows people to anything they want with your software which includes distributing closed source versions while the later is a copyleft license which mandates that any work derived from the software is also open source i.e., the user cannot create a closed source code using your software. 

If you still can't make up your mind between MIT or GNU GPL or want more choices and further information, this website might be useful: [Choose an opensource license](https://choosealicense.com/licenses/)

This link provides a brief summary on applying a license to your software: https://www.gnu.org/licenses/gpl-howto.html
## Citing code
To understand the best practices for citing software, refer to this article.

Katz et. al. (2021) Recognizing the value of software: a software citation guide [version 2; peer review: 2 approved]. F1000Research 9:1257 DOI: https://doi.org/10.12688/f1000research.26932.2  

## Example Respositories
* [RawHash](https://github.com/CMU-SAFARI/RawHash) - A hash-based mechanism to map raw nanopore signals to a reference genome in real-time.
* [Generalizable deep learning model for early Alzheimer’s disease detection from structural MRIs](https://github.com/NYUMedML/CNN_design_for_AD) - A deep learning model compared with exisiting brain volume/thickness models on external independent cohort from [NACC](https://naccdata.org/)
* [AI-based differential diagnosis of dementia etiologies on multimodal data](https://github.com/vkola-lab/nmed2024) - A deep learning framework for the differential diagnosis of dementia etiologies using multi-modal data.
* Large Journal Repository containing numerous example repositories - [ElsevierSoftwareX](https://github.com/ElsevierSoftwareX)

## References
1. [UK DRI Guidelines and policy documents on Data/Code sharing](https://github.com/UKDRI/Guidelines-and-policies) 
2. [How to archive Github code with Zenodo and get a DOI](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)
4. [Software Deposit Guidance for Researchers](https://zenodo.org/records/1327312)
