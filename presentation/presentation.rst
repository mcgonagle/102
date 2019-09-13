:title: Armory Training Update
:author: Thomas A. McGonagle
:keywords: Spinnaker
:skip-help: true
:css: presentation.css

.. header::
    .. image:: images/Armory_logo.gif 
        :height: 300px
        :width: 600px
        :align: center

.. footer::
    .. image:: images/spinnaker.png 
        :height: 75px
        :width: 90px
        :align: center
    

----

:id: title-slide

Armory Training Update 
======================
9/13/19
-------

.. note::

  * note

----

:id: who-am-i

whoami?
=======
Thomas A. McGonagle
-------------------
Solutions Architect
-------------------
thomas.mcgonagle@armory.io
--------------------------
@mcgonagle
----------


.. note::
  * note

----

:id: spinnaker-metaphor

Spinnaker Metaphor
========================

.. image:: images/waterworld.jpg 
    :height: 600px
    :width: 400px

.. note::
  * note

----

:id: class-intro

Class Introductions
===================

* Name

* Role

* Experience with DevOps

* Super Power of Choice/Favorite Terrible Movie

.. note::

  * note

----

:id: training-goals

Training Goals
==============

* Grok Spinnaker

* ??

.. image:: images/grok.png
    :height: 300px
    :width: 900px
    :align: right

.. note::

  * note

----

:id: training-philosophy

Training Philosophy
===================

.. image:: images/grampy.png 
    :height: 175px
    :width: 250px
    :align: left



.. image:: images/socrates.png 
    :height: 175px
    :width: 250px
    :align: right


----

:id: devops-definition

DevOps Definition
=================

Technical and **Cultural** focus on **Teamwork** and the software delivery **Mission** 
--------------------------------------------------------------------------------------

.. note::

    * note


----

:id: devops-tenants

DevOps Tenants - ACAMS+
=======================

* Agile
* Culture
* Automation
* Metrics
* Sharing
* Plus...

.. note::

    * note

----

:id: devops-practices

DevOps Practices
=======================

.. image:: images/devops_playbook.png 
    :height: 600px
    :width: 1200px
    :align: left

.. note::

    * note

----

:id: migrating-to-the-cloud

Migrating to the Cloud
======================

.. image:: images/migrating_to_the_cloud.png 
    :height: 640px
    :width: 1080px
    :align: center

.. note::

    * note

----

:id: hovercaft

hovercraft
==========

https://hovercraft.readthedocs.io/en/latest/index.html

.. note::

    * note

----

:id: continuous-improvement 

Continuous Improvement
======================

.. image:: https://www.planview.com/wp-content/uploads/2018/09/what-is-continuous-improvement-leankit.jpg
    :height: 600px
    :width: 1200px
    :align: center

.. note::

    * note

----

:id: dog-food

Dog Food
========

.. image:: https://images-na.ssl-images-amazon.com/images/I/81XPwF8NnAL._SL1500_.jpg
    :height: 600px
    :width: 800px
    :align: center

.. note::

    * note

----

:id: ci-cd

CI/CD
========

.. image:: https://www.talend.com/wp-content/uploads/DevOps-Talend-1.png
    :height: 600px
    :width: 1200px
    :align: center

.. note::

    * note

----

:id: k8s

k8s
===

.. code:: python

    docker build --tag=mcgonagle/102 .

    docker push mcgonagle/102:latest

    kubectl run hovercraft --image=mcgonagle/102 -n default

    kubectl -n default expose deployment/hovercraft --port=9000 --target-port=9000

    kubectl -n default port-forward services/hovercraft 9000:9000

.. note::

    * note

----

:id: headers

Headers
=======

.. code:: python
    
    This becomes a h1
    =================

    And this a h2
    -------------

.. note::

    * note

----

:id: bullets

bullets
=======

.. code:: python

    * Bullet 1

        * Bullet 1.1

    * Bullet 2

    * Bullet 3

.. note::

    * note

----

:id: lists

lists
=======

.. code:: python

    1. Item 1

        1.1. Item 1.1

    2. Item 2

    3. Item 3

.. note::

    * note

----

:id: images

images
======

.. code:: python

    .. image:: path/to/image.png
        :height: 600px
        :width: 800px

.. note::

    * note

----

:id: questions

Questions?
==========

Presentation available at: https://github.com/mcgonagle/102

.. note::

    * note