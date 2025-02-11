Welcome to AI4OS documentation!
===============================

.. admonition:: Useful links
   :class: important

    | :fa:`home` `Homepage <https://ai4eosc.eu/>`__
    |   A high level overview of the project.
    | :fa:`book` `Documentation <https://docs.ai4eosc.eu/>`__
    |   The main source of knowledge on how to use the project. Refer always to here in case of doubt.
    | :fa:`id-badge` :doc:`Authentication <user/overview/auth>`
    |   The authentication management for accessing the AI4OS stack.
    | :fa:`sliders` :doc:`Dashboard <user/overview/dashboard>`
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
    for a quick overview of the project from the user's point of view (`attached slides <https://cdn.jsdelivr.net/gh/ai4eosc/ai4-docs@master/source/_static/overview.pdf>`__).

.. important::

   A quick note on terminology. ``AI4OS`` is the name of the generic software stack that is
   powering the deployments of different platforms (``AI4EOSC``, ``iMagine``).
   So for example the **AI4OS Dashboard** is the component that can be deployed as the
   **AI4EOSC Dashboard** or the **iMagine Dashboard**.
   These platform-specific Dashboards can have minor customizations but the underlying
   technology remains the same.

   Current supported platforms:

   * `AI4EOSC <https://ai4eosc.eu/>`__: AI for the European Open Science Cloud
   * `iMagine <https://imagine-ai.eu/>`__: Imaging data and services for aquatic science


User documentation
------------------

If you are a user (current or potential) you should :doc:`start here <user/index>`.

.. toctree::
   :maxdepth: 3

   user/index

Component documentation
-----------------------

Individual components' documentation can be found here:

* `DEEPaaS documentation <https://docs.deep-hybrid-datacloud.eu/projects/deepaas/>`__


Technical documentation
-----------------------

If you are searching for technical notes on various areas, please check the
following section.

.. toctree::
   :maxdepth: 3

   technical/index

Indices and tables
==================

* :ref:`genindex`
* :ref:`search`
