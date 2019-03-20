# Copyright 2019 ahmong. All rights reserved.
# A php platform for moodle.
#
# Copyright 2015 tsuru authors. All rights reserved.
# Use of this source code is governed by a BSD-style
# license that can be found in the LICENSE file.

FROM  tsuru/base-platform:18.04
ADD	. /var/lib/tsuru/phpmdl
RUN ls /var/lib/tsuru/phpmdl
RUN	sudo cp /var/lib/tsuru/phpmdl/deploy /var/lib/tsuru
RUN set -ex; \
    sudo /var/lib/tsuru/phpmdl/install; \
    sudo rm -rf /var/lib/apt/lists/*
