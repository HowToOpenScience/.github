# How to Open Science

[![OSF][badge]][osf]

'How to Open Science'[^disclaimer] is an alias used to easily identify research related to the advancement of open science, reproducibility, and replicability in disciplines. The goal of this group is to gather and inform others on research conducted on open science, promote practices and more robust metrics for reproducibility and replicability, and to analyze the current state of disciplines in adoption of these practices.

This project serves as the repository holding the webpage. The rendered version can be viewed at https://howtoopenscience.com.

Currently, this group is focused on these goals in the following disciplines and conferences:

* Education Technology and Learning Sciences
    * [International Conference on Learning Analytics and Knowledge][lak]
    * [International Conference on Artificial Intelligence in Education][aied]
    * [International Conference on Educational Data Mining][edm]
    * [ACM Conference on Learning @ Scale][lats]

## Organizers

* [Aaron Haim][ahaim-site] (Worcester Polytechnic Institute)
* [Stacy T. Shaw][sshaw-site] (Worcester Polytechnic Institute)
* [Neil T. Heffernan III][nheffernan-site] (Worcester Polytechnic Institute)

## License

The content of this Open Science Framework project and all subprojects is under the [Creative Commons Attribution 4.0 International License][license] unless otherwise specified.

# Local Setup

### [Docker][docker] Container

Clone this repository and run the following commands:

```
docker build -t <image_name> .
docker run --rm -it -p 8000:8000 -v ${PWD}/src:/docs <image_name>
```

`image_name` can be specified to whatever identifier the user desires. This will run the docs server and expose it to the local host on port 8000.

### Python

This setup runs in Python 3.9.5. You can install the required libraries through the provided `requirements.txt`:

```
pip install -r requirements.txt
```

Then navigate to the  `src` folder in your terminal and serve the docs.

```
cd ./src
mkdocs serve
```

> You may need to prefix the `pip` or `mkdocs` command with either `python3 -m` for Unix systems or `py -m` for Windows systems if the python modules were not properly installed onto the path.

## Attributions

* The [organization icon][icon] [IconPark Outline unlock-one][icon-location] is provided under the [Apache-2.0 License][icon-license]. The icon was transformed into a 1000 x 1000 PNG file and made white with a gray background.

## Citation

```
@misc{Haim_Shaw_Heffernan_2022,
  title={How to Open Science},
  url={osf.io/ye54u},
  DOI={10.17605/OSF.IO/YE54U},
  publisher={OSF},
  author={Haim, Aaron and Shaw, Stacy T and Heffernan, Neil T, III},
  year={2022},
  month={Nov}
}
```

[^disclaimer]: 'How to Open Science' is not a copyrighted or trademarked phrase. Feel free to use it.

[badge]: https://img.shields.io/badge/OSF-10.17605%2Fosf.io%2Fye54u-blue
[osf]: https://doi.org/10.17605/osf.io/ye54u

[lak]: https://www.solaresearch.org/events/lak/
[aied]: https://iaied.org/
[edm]: https://educationaldatamining.org/
[lats]: https://learningatscale.acm.org/

[ahaim-site]: https://ahaim.ashwork.net/
[sshaw-site]: https://sites.google.com/view/stacytshaw
[nheffernan-site]: https://www.neilheffernan.net/

[docker]: https://www.docker.com/

[license]: ../LICENSE

[icon]: ../assets/icon/unlock-one.png
[icon-location]: https://github.com/bytedance/IconPark
[icon-license]: https://github.com/bytedance/IconPark/blob/master/LICENSE
