load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "lattice_planner",
    srcs = [
        "lattice_planner.cc",
    ],
    hdrs = [
        "lattice_planner.h",
    ],
    deps = [
        "//modules/common:log",
        "//modules/common/adapters:adapter_manager",
        "//modules/common/vehicle_state:vehicle_state_provider",
        "//modules/planning/common:planning_gflags",
        "//modules/planning/constraint_checker",
        "//modules/planning/constraint_checker:collision_checker",
        "//modules/planning/lattice/behavior_decider",
        "//modules/planning/lattice/behavior_decider:path_time_graph",
        "//modules/planning/lattice/trajectory_generator:backup_trajectory_generator",
        "//modules/planning/lattice/trajectory_generator:trajectory1d_generator",
        "//modules/planning/lattice/trajectory_generator:trajectory_combiner",
        "//modules/planning/lattice/trajectory_generator:trajectory_evaluator",
        "//modules/planning/lattice/util:lattice_trajectory1d",
        "//modules/planning/planner",
        "//modules/planning/proto:planning_proto",
    ],
)

cpplint()
