#
# Copyright 2019 The Project Oak Authors
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

package(
    default_visibility = ["//visibility:public"],
)

load(
    "@com_github_grpc_grpc//bazel:grpc_build_system.bzl",
    "grpc_proto_library",
)

proto_library(
    name = "private_set_intersection_proto",
    srcs = ["private_set_intersection.proto"],
    deps = [
        "@com_google_protobuf//:empty_proto",
    ],
)

grpc_proto_library(
    name = "private_set_intersection_proto_grpc",
    srcs = ["private_set_intersection.proto"],
    has_services = True,
    well_known_protos = True,
    deps = [],
)
