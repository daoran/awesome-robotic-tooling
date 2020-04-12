# Awesome Robotic Tooling [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Just a bunch of powerful robotic resources and tools for professional development with ROS in C++ and Python.

> [Unix philosophy](https://en.wikipedia.org/wiki/Unix_philosophy) - about the concept of software tooling 

* [Coordination and Communication](#coordination-and-communication)
* [Documentation and Presentation](#documentation-and-presentation)
* [Architecture and Design](#architecture-and-design)
* [Safety](#safety)
* [Framework](#framework)
* [Development Environment](#development-environment)
   * [Code and Run](#code-and-run)
   * [Template](#template)
   * [Build and Deploy](#build-and-deploy)
   * [Unit and Integration Test](#unit-and-integration-test)
   * [Lint and Format](#lint-and-format)
   * [Launch and Monitor](#launch-and-monitor)
   * [Debugging and Tracing](#debugging-and-tracing)
   * [Version Control](#version-control)
   * [Simulation](#simulation)
* [Hardware](#hardware)
   * [Calibration and Transformation](#calibration-and-transformation)
* [Sensor Processing](#sensor-processing)
   * [Perception Pipeline](#perception-pipeline)
   * [Parallel Processing](#parallel-processing)
   * [Machine Learning](#machine-learning)
   * [Radar Processing](#radar-processing)
   * [Image Processing](#image-processing)
   * [Point Cloud Processing](#point-cloud-processing)
   * [Localization](#localization)
   * [SLAM](#slam)
      * [Lidar](#lidar)
      * [Camera](#camera)
      * [Static Maps](#static-maps)
* [Behavior and Decision](#behavior-and-decision)
* [Planning and Control](#planning-and-control)
* [User Interaction](#user-interaction)
   * [Graphical User Interface](#graphical-user-interface)
   * [Command Line Interface](#command-line-interface)
   * [Annotation](#annotation)
   * [Visualization](#visualization)
      * [Point Cloud](#point-cloud)
      * [RViz](#rviz)
* [Operation System](#system)
   * [Monitoring](#monitoring)
   * [Storage and Record](#storage-and-record)
   * [Network Distributed File System](#network-distributed-file-system)
   * [High Performance Computing](#high-performance-computing)
   * [Embedded Operation System](#embedded-operation-system)
   * [Real-Time Kernel](#real-time-kernel)
   * [Network and Middleware](#network-and-middleware)
   * [Security](#security)
* [Datasets](#datasets)

## Coordination and Communication
* [Agile Development](https://agilemanifesto.org/) - Manifesto for Agile Software Development
* [Gitflow](https://github.com/nvie/gitflow) - Makes parallel development very easy, by isolating new development from finished work
* [DeepL](https://github.com/uinput/deeplator) - an online translator that outperforms Google, Microsoft and Facebook
* [Taiga](https://github.com/benhutchins/docker-taiga) - Agile Projectmanagment Tool
* [Kanboard](https://github.com/kanboard/kanboard) - Minimalistic Kanban Board
* [kanban](https://gitlab.com/leanlabsio/kanban) - Free, open source, self-hosted, Kanban board for GitLab issues
* [Gitlab](https://github.com/sameersbn/docker-gitlab) - Simple Selfhosted Gitlab Server with Docker
* [Gogs](https://github.com/gogs/gogs) - Aims to build a simple, stable and extensible self-hosted Git service that can be setup in the most painless way
* [Woost](https://woost.space/) - Workflow Automation, Collaboration with Externals
* [Wekan](https://github.com/wekan/wekan) - Meteor based Kanban Board
* [JIRA API](https://github.com/pycontribs/jira) - Python Library for REST API of Jira
* [Taiga API](https://github.com/nephila/python-taiga) - Python Library for REST API of Taiga
* [Chronos-Timetracker](https://github.com/web-pal/chronos-timetracker)  - Desktop client for JIRA. Track time, upload worklogs without a hassle
* [Grge](https://gitlab.com/ApexAI/grge) - Grge is a daemon and command line utility augmenting GitLab
* [gitlab-triage](https://gitlab.com/gitlab-org/gitlab-triage) - GitLab's issues and merge requests triage, automated!
* [Helpy](https://github.com/helpyio/helpy) - is a modern, open source helpdesk customer support application
* [ONLYOFFICE](https://github.com/ONLYOFFICE/CommunityServer) -  is a free open source collaborative system developed to manage documents, projects, customer relationship and email correspondence, all in one place.
* [discourse](https://github.com/discourse/discourse) - A platform for community discussion. Free, open, simple
* [Gerrit](https://gerrit.googlesource.com/gerrit/) - is a code review and project management tool for Git based projects
* [jitsi-meet](https://github.com/jitsi/jitsi-meet) - Secure, Simple and Scalable Video Conferences that you use as a standalone app or embed in your web application
* [mattermost](https://github.com/mattermost/mattermost-server) - is an open source, private cloud, Slack-alternative

## Documentation and Presentation
* [Typora](https://typora.io/) - A Minimalist Markdown Editor
* [Markor](https://github.com/gsantner/markor) - A Simple Markdown Editor for your Android Device
* [Pandoc](https://github.com/jgm/pandoc) - Universal markup converter
* [Yaspeller](https://github.com/hcodes/yaspeller) - Command line tool for spell checking
* [ReadtheDocs](https://docs.readthedocs.io/en/stable/development/buildenvironments.html) - Build your local ReadtheDocs Server
* [Doxygen](https://github.com/doxygen/doxygen) - Doxygen is the de facto standard tool for generating documentation from annotated C++ sources
* [Sphinx](https://github.com/sphinx-doc/sphinx/) - is a tool that makes it easy to create intelligent and beautiful documentation for Python projects
* [Word-to-Markdown](https://github.com/benbalter/word-to-markdown) - A ruby gem to liberate content from Microsoft Word document
* [carbon](https://github.com/carbon-app/carbon) - Share beautiful images of your source code
* [undraw](https://undraw.co/illustrations) - Free Professional business SVGs easy to customize
* [asciinema](https://github.com/asciinema/asciinema) - lets you easily record terminal sessions and replay them in a terminal as well as in a web browser.
* [inkscape](https://inkscape.org/) - Inkscape is a professional vector graphics editor for Linux, Windows and macOS
* [Reveal-Hugo](https://github.com/dzello/reveal-hugo) - A Hugo theme for Reveal.js that makes authoring and customization a breeze. With it, you can turn any properly-formatted Hugo content into a HTML presentation.
* [Hugo-Webslides](https://github.com/RCJacH/hugo-webslides) - This is a Hugo template to create WebSlides presentation using markdown.
* [jupyter2slides](https://github.com/datitran/jupyter2slides) - Cloud Native Presentation Slides with Jupyter Notebook + Reveal.js
* [patat](https://github.com/jaspervdj/patat) - Terminal-based presentations using Pandoc
* [github-changelog-generator](https://github.com/github-changelog-generator/github-changelog-generator) - Automatically generate change log from your tags, issues, labels and pull requests on GitHub. 
* [GitLab-Release-Note-Generator](https://github.com/jk1z/GitLab-Release-Note-Generator) - A Gitlab release note generator that generates release note on latest tag
* [OCRmyPDF](https://github.com/jbarlow83/OCRmyPDF) - adds an OCR text layer to scanned PDF files, allowing them to be searched
* [papermill](https://github.com/nteract/papermill) - is a tool for parameterizing, executing, and analyzing Jupyter Notebooks.
* [docs](https://github.com/google/docsy-example) - An example documentation site using the Docsy Hugo theme
* [overleaf](https://www.overleaf.com/project) - The easy to use, online, collaborative LaTeX editor

## Architecture and Design
* [Guidelines](https://github.com/S2-group/icse-seip-2020-replication-package/blob/master/ICSE_SEIP_2020.pdf) - on how to architect ROS-based systems
* [yed](https://www.yworks.com/products/yed) - yEd is a powerful desktop application that can be used to quickly and effectively generate high-quality diagrams
* [yed_py](https://github.com/true-grue/yed_py) - Generates graphML that can be opened in yEd
* [Plantuml](https://github.com/plantuml/plantuml-server) - Web application to generate UML diagrams on-the-fly in your live documentation	
* [rqt_graph](https://wiki.ros.org/rqt_graph) - rqt_graph provides a GUI plugin for visualizing the ROS computation graph
* [rqt_launchtree](https://github.com/pschillinger/rqt_launchtree) - An RQT plugin for hierarchical launchfile configuration introspection.
* [cpp-dependencies](https://github.com/tomtom-international/cpp-dependencies) - Tool to check C++ #include dependencies (dependency graphs created in .dot format)
* [pydeps](https://github.com/thebjorn/pydeps) - Python Module Dependency graphs
* [aztarna](https://github.com/aliasrobotics/aztarna) -  a footprinting tool for robots.
* [draw.io](https://www.draw.io/) - is free online diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams 
* [capella](https://www.eclipse.org/capella/) - Comprehensive, extensible and field-proven MBSE tool and method
to successfully design systems architecture
* [robmosys](https://robmosys.eu/) - RobMoSys envisions an integrated approach built on top of the current code-centric robotic platforms, by applying model-driven methods and tools
* [Papyrus for Robotics](https://www.eclipse.org/papyrus/components/robotics/) - is graphical editing tool for robotic applications that complies with the RobMoSys approach
* [fossology](https://github.com/fossology/fossology) - a toolkit you can run license, copyright and export control scans from the command line

### Safety
* [awesome-safety-critical](https://github.com/stanislaw/awesome-safety-critical) - List of resources about programming practices for writing safety-critical software.
* [open-autonomous-safety](https://github.com/voyage/open-autonomous-safety) - OAS is a fully open-source library of Voyage’s safety processes and testing procedures, designed to supplement existing safety programs at self-driving car startups across the world.
* [CarND-Functional-Safety-Project](https://github.com/udacity/CarND-Functional-Safety-Project) - Create functional safety documents in this Udacity project
* [Automated Valet Parking Safety Documents](https://avp-project.uk/publication-of-safety-documents) - Automated Valet Parking Safety Documents
* [safe_numerics](https://github.com/boostorg/safe_numerics) - Replacements to standard numeric types which throw exceptions on errors
* [Air Vehicle C++ development coding standards](http://www.stroustrup.com/JSF-AV-rules.pdf) - Provide direction and guidance to C++ programmers that will enable them to employ good programming style and proven programming practices leading to safe, reliable, testable, and maintainable code
* [AUTOSAR Coding Standard](https://www.autosar.org/fileadmin/user_upload/standards/adaptive/17-10/AUTOSAR_RS_CPP14Guidelines.pdf) - Guidelines for the use of the C++14 language in critical and safety-related system

## Framework
* [ROS](https://github.com/ros) - (Robot Operating System) provides libraries and tools to help software developers create robot applications
* [awesome-ros2](https://github.com/fkromer/awesome-ros2) - A curated list of awesome Robot Operating System Version 2.0 (ROS 2) resources and libraries.
* [OpenPilot](https://github.com/commaai/openpilot) - Open Source Adaptive Cruise Control (ACC) and Lane Keeping Assist System (LKAS) 
* [Apollo](https://github.com/ApolloAuto/apollo) - High performance, flexible architecture which accelerates the development, testing, and deployment of Autonomous Vehicles.
* [Autoware.ai](https://gitlab.com/autowarefoundation/autoware.ai) - Autoware.AI is the world's first "All-in-One" open-source software for autonomous driving technology
* [AutowareAuto](https://autowareauto.gitlab.io/AutowareAuto/) - It is a clean slate rewrite of Autoware. Autoware.Auto applies best-in-class software engineering.
* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/) - This is a Python code collection of robotics algorithms, especially for autonomous navigation.
* [Stanford Self Driving Car Code](https://github.com/emmjaykay/stanford_self_driving_car_code) - Stanford Code From Cars That Entered DARPA Grand Challenges
* [astrobee](https://github.com/nasa/astrobee) - Astrobee is a free-flying robot designed to operate as a payload inside the International Space Station (ISS).
* [CARMAPlatform](https://github.com/usdot-fhwa-stol/CARMAPlatform) - enables cooperative automated driving plug-in
* [Automotive Grade Linux](https://www.automotivelinux.org/) - Automotive Grade Linux is a collaborative open source project that is bringing together automakers, suppliers and technology companies to accelerate the development and adoption of a fully open software stack for the connected car
* [PX4](https://github.com/PX4/Firmware) - is an open source flight control software for drones and other unmanned vehicles

## Development Environment
### Code and Run
* [Vim-ros](https://github.com/taketwo/vim-ros) - Vim plugin for ROS development
* [Visual Studio Code](https://github.com/Microsoft/vscode) - Code editor for edit-build-debug cycle.
* [atom](https://github.com/atom/atom) - Hackable text editor for the 21st century
* [Teletype](https://github.com/atom/teletype) - Share your workspace with team members and collaborate on code in real time in Atom
* [Sublime](https://www.sublimetext.com/) - A sophisticated text editor for code, markup and prose
* [ade-cli](https://gitlab.com/ApexAI/ade-cli) - The ADE Development Environment (ADE) uses docker and Gitlab to manage environments of per project development tools and optional volume images
* [recipe-wizard](https://github.com/trn84/recipe-wizard) - A Dockerfile generator for running OpenGL (GLX) applications with nvidia-docker2, CUDA, ROS, and Gazebo on a remote headless server system
* [Jupyter ROS](https://github.com/RoboStack/jupyter-ros) - Jupyter widget helpers for ROS, the Robot Operating System
* [ros_rqt_plugin](https://github.com/ros-industrial/ros_qtc_plugin) - The ROS Qt Creator Plug-in for Python
* [xeus-cling](https://github.com/QuantStack/xeus-cling) - Jupyter kernel for the C++ programming language 
* [ROS IDEs](http://wiki.ros.org/IDEs) - This page collects experience and advice on using integrated development environments (IDEs) with ROS.
* [TabNine](https://github.com/zxqfl/TabNine) - The all-language autocompleter
* [kite](https://kite.com/) - Use machine learning to give you 
 useful code completions for Python
* [jedi](https://github.com/davidhalter/jedi) - Autocompletion and static analysis library for python
* [roslibpy](https://github.com/gramaziokohler/roslibpy) - Python ROS Bridge library allows to use Python and IronPython to interact with ROS, the open-source robotic middleware. 
* [pybind11](https://github.com/pybind/pybind11) - Seamless operability between C++11 and Python
* [Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail) - free and open-source cross-platform source explorer
* [rebound](https://github.com/shobrook/rebound) - Command-line tool that instantly fetches Stack Overflow results when an exception is thrown 
* [mybinder](https://mybinder.org/) - open notebooks in an executable environment, making your code immediately reproducible by anyone, anywhere. 
* [ROSOnWindows](https://ms-iot.github.io/ROSOnWindows/) - an experimental release of ROS1 for Windows

### Template
* [ROS](https://github.com/leggedrobotics/ros_best_practices/tree/master/ros_package_template) - Template for ROS node standardization in C++ 
* [Launch](https://wiki.ros.org/roslaunch/Tutorials/Roslaunch%20tips%20for%20larger%20projects) - Templates on how to create launch files for larger projects
* [Bash](https://github.com/ralish/bash-script-template) - A bash scripting template incorporating best practices & several useful functions
* [URDF](https://wiki.ros.org/urdf/Examples) - Examples on how to create Unified Robot Description Format (URDF) for different kinds of robots
* [Python](http://wiki.ros.org/PyStyleGuide) - Style guide to be followed in writing Python code for ROS
* [Docker](https://ade-cli.readthedocs.io/en/latest/create-custom-base-image.html) - The Dockerfile in the minimal-ade project shows a minimal example of how to create a custom base image

### Build and Deploy
* [qemu-user-static](https://github.com/multiarch/qemu-user-static) - is to enable an execution of different multi-architecture containers by QEMU and binfmt_misc
* [Cross compile ROS 2 on QNX](https://gitlab.apex.ai/snippets/63) -  introduces how to cross compile ROS 2 on QNX
* [bloom](https://github.com/ros-infrastructure/bloom) - A release automation tool which makes releasing catkin packages easier
* [superflore](https://github.com/ros-infrastructure/superflore) - An extended platform release manager for Robot Operating System    
* [catkin_tools](https://github.com/catkin/catkin_tools) - Command line tools for working with catkin
* [industrial_ci](https://github.com/ros-industrial/industrial_ci) - Easy continuous integration repository for ROS repositories
* [ros_gitlab_ci](https://gitlab.com/VictorLamoine/ros_gitlab_ci) - contains helper scripts and instructions on how to use Continuous Integration (CI) for ROS projects hosted on a GitLab instance.
* [gitlab-runner](https://gitlab.com/gitlab-org/gitlab-runner) -  runs tests and sends the results to GitLab
* [colcon-core](https://github.com/colcon/colcon-core) - command line tool to improve the workflow of building, testing and using multiple software packages
* [gitlab-release](https://gitlab.com/alelec/gitlab-release) - Simple python3 script to upload files (from ci) to the current projects release (tag)
* [clang](https://github.com/llvm-mirror/clang) -  This is a compiler front-end for the C family of languages
(C, C++, Objective-C, and Objective-C++) which is built as part of the LLVM
compiler infrastructure project
* [catkin_virtualenv](https://github.com/locusrobotics/catkin_virtualenv) - Bundle python requirements in a catkin package via virtualenv 
* [pyenv](https://github.com/pyenv/pyenv) - Simple Python version management
* [aptly](https://github.com/aptly-dev/aptly) - Debian repository management tool 
* [cross_compile](https://github.com/ros-tooling/cross_compile) - Assets used for ROS2 cross-compilation 
* [docker_images](https://github.com/osrf/docker_images) - Official Docker images maintained by OSRF on ROS(2) and Gazebo
* [robot_upstart](https://github.com/clearpathrobotics/robot_upstart) - presents a suite of scripts to assist with launching background ROS processes on Ubuntu Linux PCs
* [robot_systemd](http://docs.ros.org/kinetic/api/robot_systemd/html/#) - units for managing startup and shutdown of roscore and roslaunch
* [ryo-iso](https://ryo-iso.readthedocs.io/en/latest/) - is a modern ISO builder that streamlines the process of deploying a complete robot operating system from a yaml config file
* [network_autoconfig](http://docs.ros.org/kinetic/api/network_autoconfig/html/) - automatic configuration of ROS networking for most use cases without impacting usage that require manual configuration.

### Unit and Integration Test
* [setup-ros](https://github.com/ros-tooling/setup-ros) - This action sets up a ROS and ROS 2 environment for use in Github actions
* [UnitTesting](https://wiki.ros.org/Quality/Tutorials/UnitTesting) - This page lays out the rationale, best practices, and policies for writing and running unit tests and integration tests for ROS.
* [googletest](https://github.com/google/googletest) - Google's C++ test framework
* [pytest](https://github.com/pytest-dev/pytest/) - The pytest framework makes it easy to write small tests, yet scales to support complex functional testing 
* [doctest](https://github.com/onqtam/doctest) - The fastest feature-rich C++11/14/17/20 single-header testing framework for unit tests and TDD
* [osrf_testing_tools_cpp](https://github.com/osrf/osrf_testing_tools_cpp) - contains testing tools for C++, and is used in OSRF projects.
* [code_coverage](https://github.com/mikeferguson/code_coverage) - ROS package to run coverage testing

### Lint and Format
* [action-ros-lint](https://github.com/ros-tooling/action-ros-lint) - Github action to run linters on ROS 2 packages
* [cppcheck](https://github.com/danmar/cppcheck) - Static analysis of C/C++ code
* [hadolint](https://github.com/hadolint/hadolint) - Dockerfile linter, validate inline bash, written in Haskell 
* [shellcheck](https://github.com/koalaman/shellcheck) - a static analysis tool for shell scripts 
* [catkin_lint](https://github.com/fkie/catkin_lint) - catkin_lint checks package configurations for the catkin build system of ROS.
* [pylint](https://github.com/PyCQA/pylint/) - Pylint is a Python static code analysis tool which looks for programming errors, helps enforcing a coding standard, sniffs for code smells and offers simple refactoring suggestions.
* [black](https://github.com/psf/black) - The uncompromising Python code formatter
* [pydocstyle](https://github.com/PyCQA/pydocstyle) - pydocstyle is a static analysis tool for checking compliance with Python docstring conventions
* [haros](https://github.com/git-afsantos/haros) - H(igh) A(ssurance) ROS - Static analysis of ROS application code. 

### Launch and Monitor
* [rosmon](https://github.com/xqms/rosmon) - ROS node launcher & monitoring daemon 
* [multimaster_fkie](https://github.com/fkie/multimaster_fkie) - GUI-based management environment that is very useful to manage ROS-launch configurations and control running nodes

### Debugging and Tracing
* [heaptrack](https://github.com/KDE/heaptrack) - traces all memory allocations and annotates these events with stack traces
* [ros2_tracing](https://gitlab.com/micro-ROS/ros_tracing/ros2_tracing) - Tracing tools for ROS 2.
* [Linuxperf](http://www.brendangregg.com/linuxperf.html) - Various Linux performance material
* [lptrace](https://github.com/khamidou/lptrace) - It lets you see in real-time what functions a Python program is running
* [pyre-check](https://github.com/facebook/pyre-check) - Performant type-checking for python
* [FlameGraph](https://github.com/brendangregg/FlameGraph) - Visualize profiled code
* [gpuvis](https://github.com/mikesart/gpuvis) - GPU Trace Visualizer
* [sanitizer](https://github.com/google/sanitizers) - AddressSanitizer, ThreadSanitizer, MemorySanitizer
* [cppinsights](https://github.com/andreasfertig/cppinsights) - C++ Insights - See your source code with the eyes of a compiler
* [inspect](https://pymotw.com/2/inspect/) - The inspect module provides functions for learning about live objects, including modules, classes, instances, functions, and methods
* [Roslaunch Nodes in Valgrind or GDB](https://wiki.ros.org/roslaunch/Tutorials/Roslaunch%20Nodes%20in%20Valgrind%20or%20GDB) - When debugging roscpp nodes that you are launching with roslaunch, you may wish to launch the node in a debugging program like gdb or valgrind instead.
* [pyperformance](https://github.com/python/pyperformance) - Python Performance Benchmark Suite
* [gira](https://github.com/geohot/qira) - QIRA is a competitor to strace and gdb
* [gdb-frontend](https://github.com/rohanrhu/gdb-frontend) - GDBFrontend is an easy, flexible and extensionable gui debugger.
* [lttng](https://lttng.org/docs/) - is an open source software toolkit which you can use to simultaneously trace the Linux kernel, user applications, and user libraries.
* [ros2-performance](https://github.com/irobot-ros/ros2-performance) - allows to easily create arbitrary ROS2 systems and then measures their performance
* [bcc](https://github.com/iovisor/bcc) - Tools for BPF-based Linux IO analysis, networking, monitoring, and more

### Version Control
* [meld](https://github.com/kaiw/meld) - Meld is a visual diff and merge tool that helps you compare files, directories, and version controlled projects
* [tig](https://github.com/jonas/tig) - Text-mode interface for git 
* [gitg](https://github.com/GNOME/gitg) - is a graphical user interface for git
* [git-cola](https://github.com/git-cola/git-cola) - The highly caffeinated Git GUI
* [python-gitlab](https://github.com/python-gitlab/python-gitlab) - is a Python package providing access to the GitLab server API.
* [bfg-repo-cleaner](https://github.com/rtyley/bfg-repo-cleaner) - Removes large or troublesome blobs like git-filter-branch does, but faster.
* [nbdime](https://github.com/jupyter/nbdime) - Tools for diffing and merging of Jupyter notebooks. 
* [semantic-release](https://github.com/semantic-release/semantic-release) - Fully automated version management and package publishing
* [go-semrel-gitab](https://gitlab.com/juhani/go-semrel-gitlab) - Automate version management for Gitlab
* [Git-repo](https://gerrit.googlesource.com/git-repo/) - Git-Repo helps manage many Git repositories, does the uploads to revision control systems, and automates parts of the development workflow
* [dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a docker image

### Simulation
* [Drake](https://github.com/RobotLocomotion/drake) - Drake aims to simulate even very complex dynamics of robots
* [Webots](https://github.com/cyberbotics/webots) - Webots is an open source robot simulator compatible (among others) with [ROS](http://wiki.ros.org/webots_ros) and [ROS2](http://wiki.ros.org/webots_ros2).
* [lgsv](https://github.com/lgsvl/simulator) - LG Electronics America R&D Center has developed an HDRP Unity-based multi-robot simulator for autonomous vehicle developers.
* [carla](https://github.com/carla-simulator/carla) - Open-source simulator for autonomous driving research
* [scenario_runner](https://github.com/carla-simulator/scenario_runner) - Traffic scenario definition and execution engine 
* [deepdive](https://github.com/deepdrive/deepdrive) - End-to-end simulation for self-driving cars 
* [uuv_simulator](https://github.com/uuvsimulator/uuv_simulator) - Gazebo/ROS packages for underwater robotics simulation
* [AirSim](https://github.com/microsoft/AirSim) - Open source simulator for autonomous vehicles built on Unreal Engine 
* [self-driving-car-sim](https://github.com/udacity/self-driving-car-sim) - A self-driving car simulator built with Unity
* [ROSIntegration](https://github.com/code-iai/ROSIntegration) - Unreal Engine Plugin to enable ROS Support
* [gym-gazebo](https://github.com/erlerobot/gym-gazebo) - An OpenAI gym extension for using Gazebo known as gym-gazebo
* [highway-env](https://github.com/eleurent/highway-env)	- A collection of environments for autonomous driving and tactical decision-making tasks
* [VREP Interface](http://www.coppeliarobotics.com/helpFiles/en/rosInterf.htm) - ROS Bridge for the VREP simulator 
* [car_demo](https://github.com/osrf/car_demo) - This is a simulation of a Prius in gazebo 9 with sensor data being published using ROS kinetic.
* [sumo](https://github.com/eclipse/sumo) - Eclipse SUMO is an open source, highly portable, microscopic and continuous road traffic simulation package designed to handle large road networks
* [open-simulation-interface](https://github.com/OpenSimulationInterface/open-simulation-interface) - A generic interface for the environmental perception of automated driving functions in virtual scenarios.
* [ESIM](https://github.com/uzh-rpg/rpg_esim/) - an Open Event Camera Simulator
* [Menge](https://github.com/MengeCrowdSim/Menge) - Crowd Simulation Framework 
* [pedsim_ros](https://github.com/srl-freiburg/pedsim_ros) - Pedestrian simulator powered by the social force model for Gazebo
* [opencrg](http://www.opencrg.org/download.html) -  open file formats and open source tools for the detailed description, creation and evaluation of road surfaces
* [esmini](https://github.com/esmini/esmini) -  is a basic OpenSCENARIO player
* [OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph) - is an open source high performance 3D graphics toolkit, used by application developers in fields such as visual simulation, games, virtual reality, scientific visualization and modelling
* [morse](https://github.com/morse-simulator) - is an academic robotic simulator, based on the Blender Game Engine and the Bullet Physics engine.
* [ROSIntegrationVision](https://github.com/code-iai/ROSIntegrationVision) - Support for ROS-enabled RGBD data acquisition in Unreal Engine Projects
* [fetch_gazebo](https://github.com/fetchrobotics/fetch_gazebo) - contains the Gazebo simulation for Fetch Robotics Fetch and Freight Research Edition Robots.
* [rotors_simulator](https://github.com/ethz-asl/rotors_simulator) - provides some multirotor models

## Hardware
* [HRIM](https://github.com/AcutronicRobotics/HRIM) - An information model for robot hardware
* [URDF](https://github.com/ros/urdf) - Repository for Unified Robot Description Format (URDF) parsing code
* [phobos](https://github.com/dfki-ric/phobos) - An add-on for Blender allowing to create URDF, SDF and SMURF robot models in a WYSIWYG environment.
* [urdf-viz](https://github.com/OTL/urdf-viz) - Visualize URDF/XACRO file, URDF Viewer works on Windows/MacOS/Linux
* [solidworks_urdf_exporter](https://github.com/ros/solidworks_urdf_exporter) - SolidWorks to URDF Exporter
* [FreeCAD](https://github.com/FreeCAD/FreeCAD) - Your own 3D parametric modeler
* [kicad](http://www.kicad-pcb.org/) - A Cross Platform and Open Source Electronics Design Automation Suite
* [PcbDraw](https://github.com/yaqwsx/PcbDraw) - Convert your KiCAD board into a nice looking 2D drawing suitable for pinout diagrams
* [PandaPower](http://www.pandapower.org) - An easy to use open source tool for power system modeling, analysis and optimization with a high degree of automation.
* [LibrePCB](https://github.com/LibrePCB/LibrePCB) - A powerful, innovative and intuitive EDA tool for everyone
* [openscad](https://github.com/openscad/openscad) -  is software for creating solid 3D CAD models
* [ngspice](http://ngspice.sourceforge.net/) - is the open source spice simulator for electric and electronic circuits.

### Calibration and Transformation
* [tf2](http://wiki.ros.org/tf2) - transform library, which lets the user keep track of multiple coordinate frames over time
* [lidar_align](https://github.com/ethz-asl/lidar_align) - A simple method for finding the extrinsic calibration between a 3D lidar and a 6-dof pose sensor
* [kalibr](https://github.com/ethz-asl/kalibr) - The Kalibr visual-inertial calibration toolbox
* [Calibnet](https://github.com/epiception/CalibNet) - Self-Supervised Extrinsic Calibration using 3D Spatial Transformer Networks
* [lidar_camera_calibration](https://github.com/ankitdhall/lidar_camera_calibration) - ROS package to find a rigid-body transformation between a LiDAR and a camera
* [ILCC](https://github.com/mfxox/ILCC) - Reflectance Intensity Assisted Automatic and Accurate Extrinsic Calibration of 3D LiDAR
* [easy_handeye](https://github.com/IFL-CAMP/easy_handeye) - Simple, straighforward ROS library for hand-eye calibration
* [imu_utils](https://github.com/gaowenliang/imu_utils) - A ROS package tool to analyze the IMU performance
* [kalibr_allan](https://github.com/rpng/kalibr_allan) - IMU Allan standard deviation charts for use with Kalibr and inertial kalman filters
* [pyquaternion](https://github.com/KieranWynn/pyquaternion) - is a full-featured Python module for representing and using quaternions
* [robot_calibration](https://github.com/mikeferguson/robot_calibration/) - This package offers calibration of a number of parameters of a robot, such as: 3D Camera intrinsics, extrinsics Joint angle offsets and robot frame offsets
* [multi_sensor_calibration](https://github.com/tudelft-iv/multi_sensor_calibration/) - contains a calibration tool to calibrate a sensor setup consisting of lidars, radars and cameras

## Sensor Processing
### Perception Pipeline
* [SARosPerceptionKitti](https://github.com/appinho/SARosPerceptionKitti) - ROS package for the Perception (Sensor Processing, Detection, Tracking and Evaluation) of the KITTI Vision Benchmark Suite
* [multiple-object-tracking-lidar](https://github.com/praveen-palanisamy/multiple-object-tracking-lidar) - C++ implementation to Detect, track and classify multiple objects using LIDAR scans or point cloud
* [cadrl_ros](https://github.com/mfe7/cadrl_ros) - ROS package for dynamic obstacle avoidance for ground robots trained with deep RL
* [AugmentedAutoencoder](https://github.com/DLR-RM/AugmentedAutoencoder) - RGB-based pipeline for object detection and 6D pose estimation
* [jsk_recognition](https://github.com/jsk-ros-pkg/jsk_recognition) - is a stack for the perception packages which are used in JSK lab.
* [GibsonEnv](https://github.com/StanfordVL/GibsonEnv) - Gibson Environments: Real-World Perception for Embodied Agents

### Parallel Processing
* [dask](https://github.com/dask/dask) - Parallel computing with task scheduling for Python
* [cupy](https://github.com/cupy/cupy) - NumPy-like API accelerated with CUDA
* [thrust](https://github.com/thrust/thrust) - Thrust is a C++ parallel programming library which resembles the C++ Standard Library.
* [ArrayFire](https://github.com/arrayfire/arrayfire) - ArrayFire: a general purpose GPU library.
* [OpenMP](https://www.openmp.org/) - OpenMP is an application programming interface that supports multi-platform shared memory multiprocessing programming in C, C++, and Fortra

### Machine Learning
* [DLIB](https://github.com/davisking/dlib) - A toolkit for making real world machine learning and data analysis applications in C++
* [fastai](https://github.com/fastai/fastai) - The fastai library simplifies training fast and accurate neural nets using modern best practices.
* [tpot](https://github.com/EpistasisLab/tpot) - A Python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming
* [deap](https://github.com/DEAP/deap) - Distributed Evolutionary Algorithms in Python
* [gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms.
* [tensorflow_ros_cpp](https://github.com/tradr-project/tensorflow_ros_cpp) - A ROS package that allows to do Tensorflow inference in C++ without the need to compile TF yourself.
* [Tensorflow Federated](https://github.com/tensorflow/federated) - TensorFlow Federated (TFF) is an open-source framework for machine learning and other computations on decentralized data

### Image Processing
* [image_pipeline](https://github.com/ros-perception/image_pipeline) - fills the gap between getting raw images from a camera driver and higher-level vision processing
* [gstreamer](https://gstreamer.freedesktop.org/) - is a pipeline-based multimedia framework that links together a wide variety of media processing systems to complete complex workflows
* [ros2_openvino_toolkit](https://github.com/intel/ros2_openvino_toolkit) -  provides a ROS-adaptered runtime framework of neural network which quickly deploys applications and solutions for vision inference
* [vision_visp](https://github.com/lagadic/vision_visp) - Wraps the ViSP moving edge tracker provided by the ViSP visual servoing library into a ROS package
* [apriltag_ros](https://github.com/AprilRobotics/apriltag_ros) - A ROS wrapper of the AprilTag 3 visual fiducial detector
* [deep_object_pose](https://github.com/NVlabs/Deep_Object_Pose) - Deep Object Pose Estimation
* [DetectAndTrack](https://github.com/facebookresearch/DetectAndTrack) - Detect-and-Track: Efficient Pose
* [SfMLearner](https://github.com/tinghuiz/SfMLearner) - An unsupervised learning framework for depth and ego-motion estimation
* [imgaug](https://github.com/aleju/imgaug) - Image augmentation for machine learning experiments
* [vision_opencv](https://github.com/ros-perception/vision_opencv) - Packages for interfacing ROS with OpenCV, a library of programming functions for real time computer vision.
* [darknet_ros](https://github.com/leggedrobotics/darknet_ros) - YOLO ROS: Real-Time Object Detection for ROS
* [tf-pose-estimation](https://github.com/ildoonet/tf-pose-estimation) - Deep Pose Estimation implemented using Tensorflow with Custom Architectures for fast inference.
* [find-object](https://github.com/introlab/find-object) - Simple Qt interface to try OpenCV implementations of SIFT, SURF, FAST, BRIEF and other feature detectors and descriptors
* [yolact](https://github.com/dbolya/yolact) - A simple, fully convolutional model for real-time instance segmentation.
* [Kimera-Semantics](https://github.com/MIT-SPARK/Kimera-Semantics) - Real-Time 3D Semantic Reconstruction from 2D data
* [detectron2](https://github.com/facebookresearch/detectron2) - is a next-generation research platform for object detection and segmentation.
* [OpenVX](https://www.khronos.org/openvx/) -  enables performance and power-optimized computer vision processing, especially important in embedded and real-time use cases

### Radar Processing
* [pyroSAR](https://github.com/johntruckenbrodt/pyroSAR) - Framework for large-scale SAR satellite data processing

### Point Cloud Processing
* [cilantro](https://github.com/kzampog/cilantro) - A lean C++ library for working with point cloud data
* [open3d](https://github.com/intel-isl/Open3D) - Open3D: A Modern Library for 3D Data Processing
* [SqueezeSeg](https://github.com/BichenWuUCB/SqueezeSeg) - Implementation of SqueezeSeg, convolutional neural networks for LiDAR point clout segmentation
* [point_cloud_io](https://github.com/ANYbotics/point_cloud_io) - ROS nodes to read and write point clouds from and to files (e.g. ply, vtk).
* [python-pcl](https://github.com/strawlab/python-pcl) - Python bindings to the pointcloud library
* [libpointmatcher](https://github.com/ethz-asl/libpointmatcher) - An "Iterative Closest Point" library for 2-D/3-D mapping in Robotics
* [depth_clustering](https://github.com/PRBonn/depth_clustering) - Fast and robust clustering of point clouds generated with a Velodyne sensor. 
* [lidar-bonnetal](https://github.com/PRBonn/lidar-bonnetal) - Semantic and Instance Segmentation of LiDAR point clouds for autonomous driving
* [CSF](https://github.com/jianboqi/CSF) - LiDAR point cloud ground filtering / segmentation (bare earth extraction) method based on cloth simulation
* [robot_body_filter](https://github.com/peci1/robot_body_filter) - A highly configurable LaserScan/PointCloud2 filter that allows to dynamically remove the 3D body of the robot from the measurements.
* [grid_map](https://github.com/ANYbotics/grid_map) - Universal grid map library for mobile robotic mapping
* [elevation_mapping](https://github.com/ANYbotics/elevation_mapping) - Robot-centric elevation mapping for rough terrain navigation
* [rangenet_lib](https://github.com/PRBonn/rangenet_lib) - contains simple usage explanations of how the RangeNet++ inference works with the TensorRT and C++ interface.
* [pointcloud_to_laserscan](https://github.com/ros-perception/pointcloud_to_laserscan) - Converts a 3D Point Cloud into a 2D laser scan.
* [octomap](https://github.com/OctoMap/octomap) - An Efficient Probabilistic 3D Mapping Framework Based on Octrees
* [pptk](https://github.com/heremaps/pptk) - Point Processing Toolkit from HEREMaps
* [gpu-voxels](https://www.gpu-voxels.org/) - GPU-Voxels is a CUDA based library which allows high resolution volumetric collision detection between animated 3D models and live pointclouds from 3D sensors of all kinds.
* [spatio_temporal_voxel_layer](https://github.com/SteveMacenski/spatio_temporal_voxel_layer) - A new voxel layer leveraging modern 3D graphics tools to modernize navigation environmental representations
* [LAStools](https://github.com/LAStools/LAStools) - award-winning software for efficient LiDAR processing
* [PCDet](https://github.com/sshaoshuai/PCDet) - is a general PyTorch-based codebase for 3D object detection from point cloud. 
* [PDAL](https://github.com/PDAL/PDAL) - is a C++ BSD library for translating and manipulating point cloud data
* [PotreeConverter](https://github.com/potree/PotreeConverter) - Builds a potree octree from las, laz, binary ply, xyz or ptx files.
* [fast_gicp](https://github.com/SMRT-AIST/fast_gicp) - A collection of GICP-based fast point cloud registration algorithms
* [ndt_omp](https://github.com/koide3/ndt_omp) - Multi-threaded and SSE friendly NDT algorithm
* [spatio_temporal_voxel_layer](https://github.com/SteveMacenski/spatio_temporal_voxel_layer) - voxel layer leveraging modern 3D graphics tools to modernize navigation environmental representations
* [laser_line_extraction](https://github.com/kam3k/laser_line_extraction) - A ROS packages that extracts line segments from LaserScan messages.
* [Go-ICP](https://github.com/yangjiaolong/Go-ICP) - Implementation of the Go-ICP algorithm for globally optimal 3D pointset registration
* [PointCNN](https://github.com/yangyanli/PointCNN) - is a simple and general framework for feature learning from point clouds
* [segmenters_lib](https://github.com/LidarPerception/segmenters_lib) - The LiDAR segmenters library, for segmentation-based detection

## Localization
* [evo](https://github.com/MichaelGrupp/evo) - Python package for the evaluation of odometry and SLAM
* [robot_localization](https://github.com/cra-ros-pkg/robot_localization) - is a package of nonlinear state estimation nodes
* [fuse](https://github.com/locusrobotics/fuse) - General architecture for performing sensor fusion live on a 
robot.
* [rep-105](https://www.ros.org/reps/rep-0105.html) - Naming conventions and semantic meaning for
coordinate frames of mobile platforms used with ROS.
* [GeographicLib](https://github.com/Sciumo/GeographicLib) - A C++ library for geographic projections.
* [ntripbrowser](https://github.com/emlid/ntripbrowser) - A Python API for browsing NTRIP (Networked Transport of RTCM via Internet Protocol).
* [imu_tools](https://github.com/ccny-ros-pkg/imu_tools) - IMU-related filters and visualizers.
* [RTKLIB](https://github.com/rtklibexplorer/RTKLIB) - A version of RTKLIB optimized for single and dual frequency low cost GPS receivers, especially u-blox receivers
* [mola](https://github.com/MOLAorg/mola) - is a Modular system for Localization and Mapping
* [ai-imu-dr](https://github.com/mbrossar/ai-imu-dr) - contains the code of our novel accurate method for dead reckoning of wheeled vehicles based only on an IMU
* [Kalman-and-Bayesian-Filters-in-Python](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python) - Kalman Filter book using Jupyter Notebook

### SLAM
#### Lidar
* [loam_velodyne](https://github.com/laboshinl/loam_velodyne) - Laser Odometry and Mapping (Loam) is a realtime method for state estimation and mapping using a 3D lidar.
* [lio-mapping](https://github.com/hyye/lio-mapping) - Implementation of Tightly Coupled 3D Lidar Inertial Odometry and Mapping (LIO-mapping)
* [A-LOAM](https://github.com/HKUST-Aerial-Robotics/A-LOAM) - Advanced implementation of LOAM
* [cartographer_ros](https://github.com/googlecartographer/cartographer_ros) - Provides ROS integration for Cartographer
* [loam_livox](https://github.com/hku-mars/loam_livox) - A robust LiDAR Odometry and Mapping (LOAM) package for Livox-LiDAR
* [StaticMapping](https://github.com/EdwardLiuyc/StaticMapping) - Use LiDAR to map the static world
* [semantic_suma](https://github.com/PRBonn/semantic_suma/) - Semantic Mapping using Surfel Mapping and Semantic Segmentation
* [slam_toolbox](https://github.com/SteveMacenski/slam_toolbox) - Slam Toolbox for lifelong mapping and localization in potentially massive maps with ROS 
* [maplab](https://github.com/ethz-asl/maplab) - An open visual-inertial mapping framework.
* [hdl_graph_slam](https://github.com/koide3/hdl_graph_slam) - is an open source ROS package for real-time 6DOF SLAM using a 3D LIDAR
* [interactive_slam](https://github.com/SMRT-AIST/interactive_slam) -  In contrast to existing automatic SLAM packages, we with minimal human effort.

#### Camera
* [orb_slam_2_ros](https://github.com/appliedAI-Initiative/orb_slam_2_ros) - A ROS implementation of ORB_SLAM2
* [dso](https://github.com/JakobEngel/dso/) - Direct Sparse Odometry
* [viso2](https://github.com/srv/viso2) - A ROS wrapper for libviso2, a library for visual odometry
* [xivo](https://github.com/ucla-vision/xivo) - X Inertial-aided Visual Odometry
* [rovio](https://github.com/ethz-asl/rovio) - Robust Visual Inertial Odometry Framework
* [MIT Kimera-Semantics](https://github.com/MIT-SPARK/Kimera-Semantics) - C++ library for real-time metric-semantic visual-inertial Simultaneous Localization And Mapping (SLAM)
* [LSD-SLAM](https://github.com/tum-vision/lsd_slam) - LSD-SLAM: Large-Scale Direct Monocular SLAM is a real-time monocular SLAM 
* [CubeSLAM and ORB SLAM](https://github.com/shichaoy/cube_slam) - Monocular 3D Object Detection and SLAM Package of CubeSLAM and ORB SLAM
* [VINS-Fusion](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion) - A Robust and Versatile Multi-Sensor Visual-Inertial State Estimator
* [openvslam](https://github.com/xdspacelab/openvslam) - OpenVSLAM: A Versatile Visual SLAM Framework
* [basalt](https://gitlab.com/VladyslavUsenko/basalt) - Visual-Inertial Mapping with Non-Linear Factor Recovery
* [Kimera](https://github.com/MIT-SPARK/Kimera) - is a C++ library for real-time metric-semantic simultaneous localization and mapping, which uses camera images and inertial data to build a semantically annotated 3D mesh of the environment
* [tagslam](https://github.com/berndpfrommer/tagslam) - is a ROS-based package for Simultaneous Localization and Mapping using AprilTag fiducial markers
* [LARVIO](https://github.com/PetWorm/LARVIO) - A lightweight, accurate and robust monocular visual inertial odometry based on Multi-State Constraint Kalman Filter.

#### Static Map
* [OpenDRIVE](http://www.opendrive.org/index.html) - OpenDRIVE® is an open file format for the logical description of road networks
* [MapsModelsImporter](https://github.com/eliemichel/MapsModelsImporter) - A Blender add-on to import models from google maps
* [Lanelet2](https://github.com/fzi-forschungszentrum-informatik/Lanelet2) - Map handling framework for automated driving
* [barefoot](https://github.com/bmwcarit/barefoot) -  Online and Offline map matching that can be used stand-alone and in the cloud
* [iD](https://github.com/openstreetmap/iD) - The easy-to-use OpenStreetMap editor in JavaScript
* [segmap](https://github.com/ethz-asl/segmap) - A map representation based on 3D segments 
* [Mapbox](https://github.com/mapbox/mapbox-gl-jsMapbox) - is a JavaScript library for interactive, customizable vector maps on the web
* [osrm-backend](https://github.com/Project-OSRM/osrm-backend) - Open Source Routing Machine - C++ backend
* [robosat](https://github.com/mapbox/robosat) - Semantic segmentation on aerial and satellite imagery. Extracts features such as: buildings, parking lots, roads, water, clouds 
* [sentinelsat](https://github.com/sentinelsat/sentinelsat) - Search and download Copernicus Sentinel satellite images
* [assuremapingtools](https://github.com/hatem-darweesh/assuremapingtools) -  Desktop based tool for viewing, editing and saving road network maps for autonomous vehicle platforms such as Autoware. 
* [geopandas](https://github.com/geopandas/geopandas) - is a project to add support for geographic data to pandas objects.
* [MapToolbox](https://github.com/autocore-ai/MapToolbox) - Plugins to make Autoware vector maps in Unity 
* [imagery-index](https://github.com/ideditor/imagery-index) - An index of aerial and satellite imagery useful for mapping

## Behavior and Decision
* [Groot](https://github.com/BehaviorTree/Groot) - Graphical Editor to create BehaviorTrees. Compliant with BehaviorTree.CPP
* [BehaviorTree.CPP](https://github.com/BehaviorTree/BehaviorTree.CPP) - Behavior Trees Library in C++
* [RAFCON](https://github.com/DLR-RM/RAFCON) - Uses hierarchical state machines, featuring concurrent state execution, to represent robot programs
* [ROSPlan](https://github.com/KCL-Planning/ROSPlan) - Generic framework for task planning in a ROS system
* [ad-rss-lib](https://github.com/intel/ad-rss-lib) - Library implementing the Responsibility Sensitive Safety model (RSS) for Autonomous Vehicles 
* [FlexBE](https://flexbe.github.io/) - Graphical editor for hierarchical state machines, based on ROS's smach.
* [sts_bt_library](https://github.com/Autonomous-Logistics/sts_bt_library) - This library provides the functionality to set up your own behavior tree logic by using the defined tree structures like Fallback, Sequence or Parallel Nodes

## Planning and Control
* [pacmod](https://github.com/astuff/pacmod) -  is designed to allow the user to control a vehicle with the PACMod drive-by-wire system.
* [mpcc](https://github.com/alexliniger/MPCC) - Model Predictive Contouring Controller for Autonomous Racing
* [rrt](https://github.com/RoboJackets/rrt) - C++ RRT (Rapidly-exploring Random Tree) implementation
* [HypridAStarTrailer](https://github.com/AtsushiSakai/HybridAStarTrailer) - A path planning algorithm based on Hybrid A* for trailer truck.
* [path_planner](https://github.com/karlkurzer/path_planner) - Hybrid A* Path Planner for the KTH Research Concept Vehicle
* [open_street_map](https://github.com/ros-geographic-info/open_street_map) - ROS packages for working with Open Street Map geographic information.
* [Open Source Car Control](https://github.com/PolySync/oscc) -  is an assemblage of software and hardware designs that enable computer control of modern cars in order to facilitate the development of autonomous vehicle technology
* [fastrack](https://github.com/HJReachability/fastrack) - A ROS implementation of Fast and Safe Tracking (FaSTrack).
* [commonroad](https://commonroad.in.tum.de/) - Composable benchmarks for motion planning on roads
* [traffic-editor](https://github.com/osrf/traffic-editor) - A graphical editor for robot traffic flows.
* [steering_functions](https://github.com/hbanzhaf/steering_functions) - contains a C++ library that implements steering functions for car-like robots with limited turning radius
* [moveit](https://moveit.ros.org/) - Easy-to-use robotics manipulation platform for developing applications, evaluating designs, and building integrated products
* [flexible-collision-library](https://github.com/flexible-collision-library/fcl) - is a library for performing three types of proximity queries on a pair of geometric models composed of triangles.
* [aikido](https://github.com/personalrobotics/aikido) - Artificial Intelligence for Kinematics, Dynamics, and Optimization
* [casADi](https://github.com/casadi/casadi) - is a symbolic framework for numeric optimization implementing automatic differentiation in forward and reverse modes on sparse matrix-valued computational graphs
* [ACADO Toolkit](https://github.com/acado/acado) - is a software environment and algorithm collection for automatic control and dynamic optimization
* [control-toolbox](https://github.com/ethz-adrl/control-toolbox) - an efficient C++ library for control, estimation, optimization and motion planning in robotics.

## User Interaction
### Graphical User Interface
* [qtpy](https://github.com/spyder-ide/qtpy) - Provides an uniform layer to support PyQt5, PySide2, PyQt4 and PySide with a single codebase
* [mir](https://github.com/MirServer/mir) - Mir is set of libraries for building Wayland based shells
* [rqt](https://wiki.ros.org/rqt) - rqt is a Qt-based framework for GUI development for ROS. It consists of three parts/metapackages
* [cage](https://github.com/Hjdskes/cage) - This is Cage, a Wayland kiosk. A kiosk runs a single, maximized application.
* [chilipie](https://github.com/futurice/chilipie-kiosk) - Easy-to-use Raspberry Pi image for booting directly into full-screen Chrome
* [pencil](https://github.com/evolus/pencil) - A tool for making diagrams and GUI prototyping that everyone can use.
* [dynamic_reconfigure](https://wiki.ros.org/dynamic_reconfigure) - The focus of dynamic_reconfigure is on providing a standard way to expose a subset of a node's parameters to external reconfiguration
* [ddynamic_reconfigure](https://github.com/pal-robotics/ddynamic_reconfigure) - allows modifying parameters of a ROS node using the dynamic_reconfigure framework without having to write cfg files.

### Acoustic User Interface
* [pyo](https://github.com/belangeo/pyo) - is a Python module written in C containing classes for a wide variety of audio signal processing types
* [rhasspy](https://github.com/synesthesiam/rhasspy) - Rhasspy (pronounced RAH-SPEE) is an offline, multilingual voice assistant toolkit inspired by Jasper that works well with Home Assistant, Hass.io, and Node-RED
* [mycroft-core](https://github.com/MycroftAI/mycroft-core) - Mycroft is a hackable open source voice assistant

### Command Line
* [dotfiles of cornerman](https://github.com/cornerman/dotfiles) - Powerful zsh and vim dotfiles
* [dotbot](https://github.com/anishathalye/dotbot) - A tool that bootstraps your dotfiles
* [prompt-hjem](https://github.com/cornerman/prompt-hjem) - A beautiful zsh prompt
* [ag](https://github.com/ggreer/the_silver_searcher) - A code-searching tool similar to ack, but faster.
* [fzf](https://github.com/junegunn/fzf) - A command-line fuzzy finder
* [pkgtop](https://github.com/orhun/pkgtop) - Interactive package manager and resource monitor designed for the GNU/Linux.
* [asciimatics](https://github.com/peterbrittain/asciimatics) - A cross platform package to do curses-like operations, plus higher level APIs and widgets to create text UIs and ASCII art animations
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go package aimed at creating Console User Interfaces.
* [TerminalImageViewer](https://github.com/stefanhaustein/TerminalImageViewer)- Small C++ program to display images in a (modern) terminal using RGB ANSI codes and unicode block graphics characters
* [rosshow](https://github.com/dheera/rosshow) - Visualize ROS topics inside a terminal with Unicode/ASCII art
* [python-prompt-toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) - Library for building powerful interactive command line applications in Python
* [bash-script-template](https://github.com/ralish/bash-script-template) - A best practices Bash script template with several useful functions
* [guake](https://github.com/Guake/guake) - Drop-down terminal for GNOME
* [wemux](https://github.com/zolrath/wemux) - Multi-User Tmux Made Easy
* [tmuxp](https://github.com/tmux-python/tmuxp) -  tmux session manager built on libtmux
* [mapscii](https://github.com/rastapasta/mapscii) - World map renderer for your console
* [terminator](https://launchpad.net/terminator) - The goal of this project is to produce a useful tool for arranging terminals
* [bat](https://github.com/sharkdp/bat) - A cat(1) clone with wings.
* [fx](https://github.com/antonmedv/fx) - Command-line tool and terminal JSON viewer

### Data Visualization and Mission Control
* [xdot](https://github.com/jrfonseca/xdot.py) - Interactive viewer for graphs written in Graphviz's dot language
* [guacamole](https://guacamole.apache.org/) - clientless remote desktop gateway. It supports standard protocols like VNC, RDP, and SSH
* [ros3djs](https://github.com/RobotWebTools/ros3djs) - 3D Visualization Library for use with the ROS JavaScript Libraries
* [webviz](https://github.com/cruise-automation/webviz) - web-based visualization libraries like rviz
* [plotly.py](https://github.com/plotly/plotly.py) - An open-source, interactive graphing library for Python
* [PlotJuggler](https://github.com/facontidavide/PlotJuggler) - The timeseries visualization tool that you deserve 
* [bokeh](https://github.com/bokeh/bokeh) - Interactive Data Visualization in the browser, from Python
* [voila](https://github.com/voila-dashboards/voila) - From Jupyter notebooks to standalone web applications and dashboards
* [Pangolin](https://github.com/stevenlovegrove/Pangolin) - Pangolin is a lightweight portable rapid development library for managing OpenGL display / interaction and abstracting video input.
* [rqt_bag](http://wiki.ros.org/rqt_bag) - provides a GUI plugin for displaying and replaying ROS bag files.
* [kepler.gl](https://github.com/keplergl/kepler.gl) - Kepler.gl is a powerful open source geospatial analysis tool for large-scale data sets. 
* [qgis_ros](https://github.com/locusrobotics/qgis_ros) - Access bagged and live topic data in a highly featured GIS environment
* [openmct](https://github.com/nasa/openmct) - A web based mission control framework
* [web_video_server](https://github.com/RobotWebTools/web_video_server) - HTTP Streaming of ROS Image Topics in Multiple Formats 
* [rvizweb](https://github.com/osrf/rvizweb) - RVizWeb provides a convenient way of building and launching a web application with features similar to RViz
* [marvros](https://github.com/mavlink/mavros) - MAVLink to ROS gateway with proxy for Ground Control Station 
* [octave](https://www.gnu.org/software/octave/) - provides a convenient command line interface for solving linear and nonlinear problems numerically, and for performing other numerical experiments using a language that is mostly compatible with Matlab.
* [streetscape.gl](https://github.com/uber/streetscape.gl) - Streetscape.gl is a toolkit for visualizing autonomous and robotics data in the XVIZ protocol.

#### Annotation
* [rviz_cloud_annotation](https://github.com/RMonica/rviz_cloud_annotation) - Point cloud annotation tool based on RViz
* [PixelAnnotationTool](https://github.com/abreheret/PixelAnnotationTool) - Annotate quickly images
* [LabelImg](https://github.com/tzutalin/labelImg) - LabelImg is a graphical image annotation tool and label object bounding boxes in images
* [cvat](https://github.com/opencv/cvat) - Powerful and efficient Computer Vision Annotation Tool (CVAT)
* [point_labeler](https://github.com/jbehley/point_labeler) - Tool for labeling of a single point clouds or a stream of point clouds
* [label-studio](https://github.com/heartexlabs/label-studio) - Label Studio is a multi-type data labeling and annotation tool with standardized output format

#### Point Cloud
* [CloudCompare](https://github.com/CloudCompare/CloudCompare) - CloudCompare is a 3D point cloud (and triangular mesh) processing software.
* [Potree](https://github.com/potree/potree) - WebGL point cloud viewer for large datasets 
* [point_cloud_viewer](https://github.com/googlecartographer/point_cloud_viewer) - makes viewing massive point clouds easy and convenient
* [ParaView](https://github.com/Kitware/ParaView) - VTK-based Data Analysis and Visualization Application
* [entwine](https://github.com/connormanning/entwine/) - is a data organization library for massive point clouds, designed to conquer datasets of trillions of points as well as desktop-scale point clouds.

#### RViz 
* [mapviz](https://github.com/swri-robotics/mapviz) - Modular ROS visualization tool for 2D data.
* [rviz_cinematographer](https://github.com/AIS-Bonn/rviz_cinematographer) - Easy to use tools to create and edit trajectories for the rviz camera.
* [rviz_satellite](https://github.com/gareth-cross/rviz_satellite) - Display internet satellite imagery in RViz
* [rviz_visual_tools](https://github.com/PickNikRobotics/rviz_visual_tools) - C++ API wrapper for displaying shapes and meshes in Rviz
* [xpp](https://github.com/leggedrobotics/xpp) - visualization of motion-plans for legged robots
* [rviz stereo](http://wiki.ros.org/rviz/Tutorials/Rviz%20in%20Stereo) - 3D stereo rendering displays a different view to each eye so that the scene appears to have depth
* [jsk_visualization](https://github.com/jsk-ros-pkg/jsk_visualization) - jsk visualization ros packages for rviz and rqt

## Operation System 
### Monitoring
* [lnav](http://lnav.org/) - is an enhanced log file viewer that takes advantage of any semantic information that can be gleaned from the files being viewed, such as timestamps and log levels
* [htop](https://github.com/hishamhm/htop) - htop is an interactive text-mode process viewer for Unix systems. It aims to be a better 'top'.
* [atop](https://github.com/Atoptool/atop) - System and process monitor for Linux with logging and replay function
* [psutil](https://github.com/giampaolo/psutil) - Cross-platform lib for process and system monitoring in Python
* [gputil](https://github.com/anderskm/gputil) - A Python module for getting the GPU status from NVIDA GPUs using nvidia-smi programmically in Python
* [gpustat](https://github.com/wookayin/gpustat) -  A simple command-line utility for querying and monitoring GPU status
* [nvtop](https://github.com/Syllo/nvtop) - NVIDIA GPUs htop like monitoring tool
* [spdlog](https://github.com/gabime/spdlog) - Very fast, header-only/compiled, C++ logging library
* [ctop](https://github.com/bcicen/ctop) -  Top-like interface for container metrics 
* [ntop](https://github.com/ntop/ntopng) - Web-based Traffic and Security Network Traffic Monitoring

### Storage and Record
* [ncdu](https://dev.yorhel.nl/ncdu) - Ncdu is a disk usage analyzer with an ncurses interface
* [borg](https://github.com/borgbackup/borg) - Deduplicating archiver with compression and authenticated encryption
* [bag-database](https://github.com/swri-robotics/bag-database) - A server that catalogs bag files and provides a web-based UI for accessing them
* [marv-robotics](https://gitlab.com/ternaris/marv-robotics) - MARV Robotics is a powerful and extensible data management platform
* [kitti2bag](https://github.com/tomas789/kitti2bag) - Convert KITTI dataset to ROS bag file the easy way!
* [pykitti](https://github.com/utiasSTARS/pykitti) - Python tools for working with KITTI data
* [rosbag_editor](https://github.com/facontidavide/rosbag_editor) - Create a rosbag from a given one, using a simple GUI
* [nextcloud](https://github.com/nextcloud/server) - Nextcloud is a suite of client-server software for creating and using file hosting services.
* [ros_type_introspection](https://github.com/facontidavide/ros_type_introspection) - Deserialize ROS messages that are unknown at compilation time
* [syncthing](https://github.com/syncthing/syncthing) - is a continuous file synchronization program
* [rqt_bag_exporter](https://gitlab.com/InstitutMaupertuis/rqt_bag_exporter) - Qt GUI to export ROS bag topics to files (CSV and/or video)
* [xviz](https://github.com/uber/xviz) - A protocol for real-time transfer and visualization of autonomy data
* [kitti_to_rosbag](https://github.com/ethz-asl/kitti_to_rosbag) - dataset tools for working with the KITTI dataset raw data and converting it to a ROS bag. Also allows a library for direct access to poses, velodyne scans, and images. 
* [ros_numpy](https://github.com/eric-wieser/ros_numpy) - Tools for converting ROS messages to and from numpy arrays


### Network Distributed File System
* [sshfs](https://github.com/osxfuse/sshfs) - File system based on the SSH File Transfer Protocol
* [moosefs](https://github.com/moosefs/moosefs) -  a scalable distributed storage system
* [ceph](https://github.com/ceph/ceph) - is a distributed object, block, and file storage platform 
* [nfs](https://github.com/sahlberg/libnfs) - is a distributed file system protocol originally developed by Sun Microsystems 

### High Performance Computing 
* [localstack](https://github.com/localstack/localstack) - A fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline
* [nvidia-docker](https://github.com/NVIDIA/nvidia-docker) - Build and run Docker containers leveraging NVIDIA GPUs 
* [kubernetes](https://github.com/NVIDIA/kubernetes) - Production-Grade Container Scheduling and Management
* [kubeflow](https://github.com/kubeflow/kubeflow) - Machine Learning Toolkit for Kubernetes
* [log-pilot](https://github.com/AliyunContainerService/log-pilot) - Collect logs for docker containers
* [traefik](https://github.com/containous/traefik) - The Cloud Native Edge Router 
* [graylog2-server](https://github.com/Graylog2/graylog2-server) - Free and open source log management
* [ansible](https://github.com/ansible/ansible) - Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy
* [docker-py](https://github.com/docker/docker-py) - A Python library for the Docker Engine API 
* [noVNC](https://github.com/novnc/noVNC) - VNC client using HTML5
* [Slurm](https://github.com/SchedMD/slurm) - Slurm: A Highly Scalable Workload Manager
* [jupyterhub](https://github.com/jupyterhub/jupyterhub) - Multi-user server for Jupyter notebooks
* [Portainer](https://github.com/portainer/portainer)	 - Making Docker management easy
* [enroot](https://github.com/NVIDIA/enroot) - A simple, yet powerful tool to turn traditional container/OS images into unprivileged sandboxes.

### Embedded Operation System
* [awesome-embedded-linux](https://github.com/fkromer/awesome-embedded-linux) - A curated list of awesome Embedded Linux resources
* [vxworks7-ros2-build](https://github.com/Wind-River/vxworks7-ros2-build) - Build system to automate the build of VxWorks 7 and ROS2 
* [Yocto](https://git.yoctoproject.org/) - Produce tools and processes that enable the creation of Linux distributions for embedded software that are independent of the underlying architecture of the embedded hardware
* [Automotive Graded Linux](https://www.automotivelinux.org/software) - is a collaborative open source project that is bringing together automakers, suppliers and technology companies to build a Linux-based, open software platform for automotive applications that can serve as the de facto industry standard
* [ROSBerryPI](http://wiki.ros.org/ROSberryPi/Installing%20ROS%20Kinetic%20on%20the%20Raspberry%20Pi) - Installing ROS Kinetic on the Raspberry Pi
* [bitbake](https://github.com/openembedded/bitbake) - is a generic task execution engine that allows shell and Python tasks to be run efficiently and in parallel while working within complex inter-task dependency constraints.
* [Jailhouse](https://github.com/siemens/jailhouse) - Jailhouse is a partitioning Hypervisor based on Linux
* [Xen](https://wiki.debian.org/Xen) - is an open-source (GPL) type-1 or baremetal hypervisor
* [QEMU](https://www.qemu.org/) - is a generic and open source machine emulator and virtualizer
* [rosserial](https://github.com/ros-drivers/rosserial) - A ROS client library for small, embedded devices, such as Arduino
* [meta-ros](https://github.com/ros/meta-ros/tree/thud-draft) - OpenEmbedded Layer for ROS Applications
* [meta-balena](https://github.com/balena-os/meta-balena) - Run Docker containers on embedded devices
* [micro-ros](https://micro-ros.github.io/) - The major changes compared to "regular" ROS 2 is that micro-ROS uses a Real-Time Operating System (RTOS) instead of Linux, and DDS for eXtremely Resource Constrained Environments
* [nvidia-container-runtime](https://github.com/NVIDIA/nvidia-container-runtime/) - NVIDIA Container Runtime is a GPU aware container runtime, compatible with the Open Containers Initiative (OCI) specification used by Docker, CRI-O, and other popular container technologie
* [fusesoc](https://github.com/olofk/fusesoc) - Package manager and build abstraction tool for FPGA/ASIC development
* [jetson_easy](https://github.com/rbonghi/jetson_easy) - Automatically script to setup and configure your NVIDIA Jetson

### Real-Time Kernel
* [ELISA](https://elisa.tech/) -  Project is to make it easier for companies to build and certify Linux-based safety-critical applications – systems whose failure could result in loss of human life, significant property damage or environmental damage
* [PREEMPT_RT kernel patch](https://wiki.linuxfoundation.org/realtime/documentation/start) - Aim of the PREEMPT_RT kernel patch is to minimize the amount of kernel code that is non-preemptible

### Network and Middleware
* [pyshark](https://github.com/KimiNewt/pyshark) - Python wrapper for tshark, allowing python packet parsing using wireshark dissectors
* [pingtop](https://github.com/laixintao/pingtop) - Ping multiple servers and show results in a top-like terminal UI
* [termshark](https://github.com/gcla/termshark) - A terminal UI for tshark, inspired by Wireshark
* [nethogs](https://github.com/raboof/nethogs) - It groups bandwidth by process
* [canmatrix](https://github.com/ebroecker/canmatrix) - Converting CAN Database Formats .arxml .dbc .dbf .kcd
* [performance_test](https://github.com/ApexAI/performance_test) - Tool to test the performance of pub/sub based              communication frameworks.
* [realtime_support](https://github.com/ros2/realtime_support) - Minimal real-time testing utility for measuring jitter and latency.
* [tcpreplay](https://github.com/appneta/tcpreplay) - Pcap editing and replay tools
* [iperf](https://github.com/esnet/iperf) - A TCP, UDP, and SCTP network bandwidth measurement tool
* [can-utils](https://github.com/linux-can/can-utils) - Linux-CAN / SocketCAN user space applications
* [ros_canopen](https://github.com/ros-industrial/ros_canopen) - CANopen driver framework for ROS
* [decanstructor](https://github.com/JWhitleyAStuff/decanstructor) - The definitive ROS CAN analysis tool
* [ros1_bridge](https://github.com/ros2/ros1_bridge) -  ROS 2 package that provides bidirectional communication between ROS 1 and ROS 2
* [Fast-RTPS](https://github.com/eProsima/Fast-RTPS) -  protocol, which provides publisher-subscriber communications over unreliable transports such as UDP, as defined and maintained by the Object Management Group (OMG) consortium
* [ptpd](https://github.com/ptpd/ptpd) - PTP daemon (PTPd) is an implementation the Precision Time Protocol (PTP) version 2 as defined by 'IEEE Std 1588-2008'. PTP provides precise time coordination of Ethernet LAN connected computers
* [wireless](https://github.com/clearpathrobotics/wireless) - Making info about wireless networks available to ROS.
* [wavemon](https://github.com/uoaerg/wavemon) - is an ncurses-based monitoring application for wireless network devices
* [protobuf](https://github.com/protocolbuffers/protobuf) - Google's data interchange format
* [CANdevStudio](https://github.com/GENIVI/CANdevStudio) -  CANdevStudio aims to be cost-effective replacement for CAN simulation software. It can work with variety of CAN hardware interfaces
* [opensplice](https://github.com/ADLINK-IST/opensplice) - Vortex OpenSplice Community Edition 
* [ros_ethercat](https://github.com/shadow-robot/ros_ethercat) - This is a reimplementation of the main loop of pr2_ethercat without dependencies on PR2 software
* [cyclonedds](https://github.com/eclipse-cyclonedds/cyclonedds) - Eclipse Cyclone DDS is a very performant and robust open-source DDS implementation
* [udpreplay](https://github.com/rigtorp/udpreplay) - Replay UDP packets from a pcap file 
* [iceoryx](https://github.com/eclipse/iceoryx) - an IPC middleware for POSIX-based systems
* [cantools](https://github.com/eerimoq/cantools) - CAN BUS tools in Python 3
* [libuavcan](https://github.com/UAVCAN/libuavcan) - is an open lightweight protocol designed for reliable communication in aerospace and robotic applications over robust vehicular networks such as CAN bus.
* [opendbc](https://github.com/commaai/opendbc) - The project to democratize access to the decoder ring of your car.
* [cabana](https://github.com/commaai/cabana) - CAN visualizer and DBC maker
* [rdbox](https://github.com/rdbox-intec/rdbox) - RDBOX is a IT infrastructure for ROS robots
* [CANopenNode](https://github.com/CANopenNode/CANopenNode) - is the internationally standardized (EN 50325-4) (CiA301) CAN-based higher-layer protocol for embedded control system.
* [uds-c](https://github.com/openxc/uds-c) - Unified Diagnostics Service (UDS) and OBD-II (On Board Diagnostics for Vehicles) C Library

### Security
* [launch_ros_sandbox](https://github.com/ros-tooling/launch_ros_sandbox) - can define launch files running nodes in restrained environments, such as Docker containers or separate user accounts with limited privileges
* [wolfssl](https://github.com/wolfSSL/wolfssl) - is a small, fast, portable implementation of TLS/SSL for embedded devices to the cloud
* [CANalyzat0r](https://github.com/schutzwerk/CANalyzat0r) - Security analysis toolkit for proprietary car protocols
* [RSF](https://github.com/aliasrobotics/RSF) - Robot Security Framework (RSF) is a standardized methodology to perform security assessments in robotics
* [How-to-Secure-A-Linux-Server](https://github.com/imthenachoman/How-To-Secure-A-Linux-Server) - An evolving how-to guide for securing a Linux server.
* [lynis](https://github.com/CISOfy/lynis) - Security auditing tool for Linux, macOS, and UNIX-based systems. Assists with compliance testing (HIPAA/ISO27001/PCI DSS) and system hardening
* [OpenVPN](https://github.com/OpenVPN/openvpn) - is an open source VPN daemon
* [openfortivpn](https://github.com/adrienverge/openfortivpn) - openfortivpn is a client for PPP+SSL VPN tunnel services and compatible with Fortinet VPNs
* [WireGuard](https://github.com/WireGuard/WireGuard) - WireGuard is a novel VPN that runs inside the Linux Kernel and utilizes state-of-the-art cryptography
* [ssh-auditor](https://github.com/ncsa/ssh-auditor) - Scans for weak ssh passwords on your network
* [vulscan](https://github.com/scipag/vulscan) - Advanced vulnerability scanning with Nmap NSE
* [nmap-vulners](https://github.com/vulnersCom/nmap-vulners) - NSE script based on Vulners.com API
* [brutespray](https://github.com/x90skysn3k/brutespray) - Automatically attempts default creds on found services.
* [fail2ban](https://github.com/fail2ban/fail2ban) - Daemon to ban hosts that cause multiple authentication errors 
* [DependencyCheck](https://github.com/jeremylong/DependencyCheck) - is a software composition analysis utility that detects publicly disclosed vulnerabilities in application dependencies
* [firejail](https://github.com/netblue30/firejail) - Firejail is a SUID sandbox program that reduces the risk of security breaches by restricting the running environment of untrusted applications using Linux namespaces, seccomp-bpf and Linux capabilities
* [RVD](https://github.com/aliasrobotics/RVD) - Robot Vulnerability Database. Community-contributed archive of robot vulnerabilities and weaknesses
* [ros2_dds_security](http://design.ros2.org/articles/ros2_dds_security.html) - adding security enhancements by defining a Service Plugin Interface (SPI) architecture, a set of builtin implementations of the SPIs, and the security model enforced by the SPIs
* [Security-Enhanced Linux](https://github.com/SELinuxProject/selinux) - is a Linux kernel security module that provides a mechanism for supporting access control security policies, including mandatory access controls (MAC)
* [OpenTitan](https://github.com/lowRISC/opentitan) - will make the silicon Root of Trust design and implementation more transparent, trustworthy, and secure for enterprises, platform providers, and chip manufacturers. OpenTitan is administered by lowRISC CIC as a collaborative project to produce high quality, open IP for instantiation as a full-featured product
* [bandit](https://github.com/PyCQA/bandit) - is a tool designed to find common security issues in Python code.

## Datasets
* [Ford Autonomous Vehicle Dataset](https://avdata.ford.com/home/default.aspx) - Ford presents a challenging multi-agent seasonal dataset collected by a fleet of Ford autonomous vehicles at different days and times.
* [awesome-robotics-datasets](https://github.com/sunglok/awesome-robotics-datasets) - A collection of useful datasets for robotics and computer vision 
* [nuscenes-devkit](https://github.com/nutonomy/nuscenes-devkit) - The devkit of the nuScenes dataset
* [utbm_robocar_dataset](https://github.com/epan-utbm/utbm_robocar_dataset) - EU Long-term Dataset with Multiple Sensors for Autonomous Driving
* [DBNet](https://github.com/driving-behavior/DBNet) - DBNet: A Large-Scale Dataset for Driving Behavior Learning
