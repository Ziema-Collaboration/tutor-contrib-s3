lemans_s3 plugin for `Tutor <https://docs.tutor.edly.io>`__
############################################################

lemans_s3 plugin for Tutor provides integration for offloading media files to Amazon S3. Principal media types offloaded include but might not be limited to:

- video transcripts
- course imports/exports
- video images
- learner profiles and profile images
- learner file submissions
- grades downloads

Note that Course Management Studio defaults the storage strategy to AWS S3 when the aws key-secret are set in cms settings

Installation
************

.. code-block:: bash

    pip install git+https://github.com/lemansfree/tutor-contrib-lemans-s3

Usage
*****

.. code-block:: bash

    tutor plugins enable lemans_s3


License
*******

This software is licensed under the terms of the AGPLv3.
