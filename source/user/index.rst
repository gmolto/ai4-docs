User documentation
==================

.. admonition:: Useful links
   :class: important

    | :fa:`home` `Homepage <https://ai4eosc.eu/>`__
    |   A high level overview of the project.
    | :fa:`book` `Documentation <https://docs.ai4eosc.eu/>`__
    |   The main source of knowledge on how to use the project. Refer always to here in case of doubt.
    | :fa:`id-badge` :doc:`Authentication <overview/auth>`
    |   The authentication management for accessing the AI4OS stack.
    | :fa:`sliders` :doc:`Dashboard <overview/dashboard>`
    |   Where users will typically search for modules developed by the community, and find the relevant pointers to use them. It allows authenticated users to deploy virtual machines on specific hardware (eg. gpus) to train a module.
    | :fa:`database` `NextCloud <https://data-deep.a.incd.pt/>`__
    |   The service that allows to store your data remotely and access them from inside your deployment.
    | :fab:`github` `Github <https://github.com/ai4eosc>`__
    |   The code of all the modules and services behind the project is stored.
    | :fab:`docker` `DockerHub <https://hub.docker.com/u/deephdc/>`__
    |   Where the Docker images of the modules are stored.
    | :fa:`timeline` `CI/CD pipeline <https://jenkins.indigo-datacloud.eu/job/Pipeline-as-code/job/DEEP-OC-org/>`__
    |   Continuous Integration and Continuous Development Jenkins instance to keep everything up-to-date with latest code changes.
    | :fa:`temperature-half` `Status of services <https://status.ai4eosc.eu/>`__
    |   Check if a specific AI4OS service might be down for some reason.
    | :fa:`folder-plus` `Module template <https://templates.cloud.ai4eosc.eu/>`__
    |   Create new modules based on our project's template.

    You can also watch this `tutorial <https://www.youtube.com/watch?v=cRMIviobF_c>`__
    for a quick overview of the project from the user's point of view (`attached slides <https://cdn.jsdelivr.net/gh/deephdc/deep-docs@master/source/_static/overview.pdf>`__).


New to the project? How about a quick dive?

.. toctree::
   :maxdepth: 2

   Quickstart <quickstart>

Overview
--------

A more in depth documentation, with detailed description on the architecture and
components is provided in the following sections.

.. toctree::
   :maxdepth: 2

   AI4OS architecture <overview/architecture>
   User roles and workflows <overview/user-roles>
   Authentication <overview/auth>
   AI4OS Modules <overview/modules>
   AI4OS Modules Template <overview/cookiecutter-template>
   DEEPaaS API <overview/api>
   AI4OS Dashboard <overview/dashboard>
   AI4OS Storage <overview/storage>

How-to's
--------

Use a model (basic user)
^^^^^^^^^^^^^^^^^^^^^^^^

.. toctree::
   :maxdepth: 2

   Perform inference locally <howto/inference-locally>
   Perform inference remotely <howto/inference-remotely>

Train a model (intermediate user)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. toctree::
   :maxdepth: 2

   Train a model locally <howto/train-model-locally>
   Train a model remotely <howto/train-model-remotely>
   Use rclone <howto/rclone>

Develop a model (advanced user)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. toctree::
   :maxdepth: 2

   Develop a model <howto/develop-model>


Use a tool (intermediate user)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

We have specific guides for each of the tools.

.. toctree::
   :maxdepth: 2

   Federated server <howto/tools/federated-server>

Others
------

.. toctree::
   :maxdepth: 2

   Useful Machine Learning resources <others/useful-ml-resources>
   Video demos <others/video-demos>
