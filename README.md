# Docs

This repository contains the documentation for the Reset Windows Update Tool. The documentation has been created using [MkDocs](https://www.mkdocs.org/) and can be viewed online at [https://docs.wureset.com/](https://docs.wureset.com/).

## Prerequisites

To build the documentation, you will need to have [Python](https://www.python.org/downloads/) installed on your machine. It's also recommended to work with a virtual environment. If you don't have a virtual environment set up, you can follow the steps in the "How to set up a virtual environment" section below.

## How to set up a virtual environment

To set up a virtual environment for this project, follow these steps:

1. Open a terminal or command prompt in the root directory of the project.
2. Install `virtualenv` with the following command:

```
pip install virtualenv
```

3. Create a new virtual environment with the following command:

```
virtualenv env
```


4. Activate the virtual environment with the following command (commands may vary depending on your operating system):

On Windows:

```
.\env\Scripts\activate
```

On Linux or macOS:

```
source env/bin/activate
```

5. You're now working in the virtual environment for this project. You can verify that you're in the virtual environment by running the following command:

```
which python
```

You should see a path that points to the virtual environment directory instead of the global Python installation.

## How to build the documentation

To build the documentation, follow these steps:

1. Clone this repository to your local machine.
2. Open a terminal or command prompt in the root directory of the cloned repository.
3. Activate the virtual environment if you haven't already (see "How to set up a virtual environment" section).
4. Run the following command to install the required dependencies for the project:

```
pip install -r requirements.txt
```

5. Run the following command to build the documentation:

```
mkdocs build
```

6. The documentation will be built and stored in the `site` folder.

## How to view the documentation

To view the documentation, follow these steps:

1. Open a terminal or command prompt in the root directory of the cloned repository.
2. Activate the virtual environment if you haven't already (see "How to set up a virtual environment" section).
3. Run the following command:

```
mkdocs serve
```

4. Open your web browser and navigate to [http://localhost:8000](http://localhost:8000).
5. You should see this documentation in your browser.

## Contributing

If you'd like to contribute to this documentation, please follow these steps:

1. Fork this repository to your own GitHub account.
2. Create a new branch with a descriptive name for your changes.
3. Make your changes and commit them to your branch.
4. Push your branch to your forked repository.
5. Open a pull request from your branch to this repository's `main` branch.
6. Your changes will be reviewed and merged if they meet the project's standards.

## Collaboration

This project has a MIT license, which means its code is open source and anyone can collaborate. If you are interested in contributing, please review the [basic collaboration rules](CODE_OF_CONDUCT.md).

Issues and feature requests can be reported through GitHub Tracker. In addition, you can join the developer community in the discussion forum, real-time chat channel, mailing list, and online meetings.

## Credits

This project is developed and maintained by [Manuel Gil](https://github.com/ManuelGil).

## License

This project is distributed under the MIT license. For more information, see the [LICENSE](LICENSE.md) file.
