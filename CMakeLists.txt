# SPDX-License-Identifier: Apache-2.0
# Copyright 2024-2026, Ne.app (amlal@nekernel.org)
# Licensed under the Apache License, Version 2.0 (see LICENSE file)
# Official repository: https://github.com/ne-app-ci/BCSABoot

if(DEFINED BCSA_FORMAT_PROFILE)

	execute_process(COMMAND ./format.sh)

elseif(DEFINED BCSA_ARM64_PROFILE)



endif()

