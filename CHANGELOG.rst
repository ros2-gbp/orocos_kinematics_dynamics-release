^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package orocos_kdl
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.3.5 (2023-03-16)
------------------
* Add changelog
* Delete manifest.xml (`#26 <https://github.com/ros2/orocos_kinematics_dynamics/issues/26>`_) (`#28 <https://github.com/ros2/orocos_kinematics_dynamics/issues/28>`_)
* Contributors: giusebar, Dharini Dutia, mergify[bot]

3.3.4 (2022-07-25)
------------------
* Update maintainers to Ivan Paunovic (`#25 <https://github.com/ros2/orocos_kinematics_dynamics/issues/25>`_)
* Merge pull request `#21 <https://github.com/ros2/orocos_kinematics_dynamics/issues/21>`_ from ros2/update_licenses (`#22 <https://github.com/ros2/orocos_kinematics_dynamics/issues/22>`_)
* Contributors: Audrow Nash, Karsten Knese

3.3.2 (2021-01-25)
------------------
* Update cmake minimum version to 2.8.12 (`#17 <https://github.com/ros2/orocos_kinematics_dynamics/issues/17>`_)
* Update maintainer (`#16 <https://github.com/ros2/orocos_kinematics_dynamics/issues/16>`_)
* Contributors: Jacob Perron, Stephen Brawner

3.3.1 (2020-05-08)
------------------
* export modern CMake interface target (`#14 <https://github.com/ros2/orocos_kinematics_dynamics/issues/14>`_)
* Contributors: Dirk Thomas

3.3.0 (2020-04-29)
------------------
* Merge pull request `#13 <https://github.com/ros2/orocos_kinematics_dynamics/issues/13>`_ from ros2/ivanpauno/sync-with-upstream
* Merge remote-tracking branch 'upstream/master' into ivanpauno/sync-with-upstrea
* Merge pull request `#221 <https://github.com/ros2/orocos_kinematics_dynamics/issues/221>`_ from sloretz/bump_cmake_cmp0048
* Use CMP0048 New behavior to suppress warning
* Merge pull request `#215 <https://github.com/ros2/orocos_kinematics_dynamics/issues/215>`_ from ros2/ivanpauno/fix-build-warning-focal
* Make it work in c++03 too
* Fix build warnings in gcc 9.2.1
* Merge pull request `#209 <https://github.com/ros2/orocos_kinematics_dynamics/issues/209>`_ from mvieth/master
* Move SVD algorithm from hpp to cpp file
* Remove wrong doc comments in ChainIKSolver
* Remove unused variable in ChainIKSolver
* Switch order in constructor to match field order
* Make parameter unsigned
* Fix/standardize whitespace and indentation
* Comment out unused parameters to avoid warnings
* Make loop variables unsigned
* Remove unnecessary semicolons
* Merge pull request `#196 <https://github.com/ros2/orocos_kinematics_dynamics/issues/196>`_ from francofusco/expose_joint_properties
* Merge pull request `#174 <https://github.com/ros2/orocos_kinematics_dynamics/issues/174>`_ from francofusco/new_tree_features
* Merge pull request `#199 <https://github.com/ros2/orocos_kinematics_dynamics/issues/199>`_ from maverick-long/fix_rotation_angle_numerical_error
* Use eigen3_cmake_module (`#11 <https://github.com/ros2/orocos_kinematics_dynamics/issues/11>`_)
* remove comment
* back to a more numerically stable method to compute the rotation angle
* Joint: getDamping() & getStiffness()
* 1.3.2
* Merge pull request `#195 <https://github.com/ros2/orocos_kinematics_dynamics/issues/195>`_ from orocos/cherry-pick-109-1.3
* fix build for missing isnan definition in newer compilers
* KDL Frames: Added Improper Rotation test for GetRotAngle
* KDL frames:  removed unnecessary epsilon checks in GetRotAngle singular case
* fix: GetRotAngle no longer causes NaNs on slightly non-orthogonal rotation matrices
* tests: added test for GetRotAngle on slightly non-orthogonal matrices
* Add edge testcase for GetRotAngle
* fix(): Orocos tests additions
* fix(): make arbitrary axis the same as for orocos convention
* fix(): disable tests in CMakeLists.txt
* fix(GetRotAngle): New GetRotAngle function to prevent erros of some flipping
* Merge pull request `#173 <https://github.com/ros2/orocos_kinematics_dynamics/issues/173>`_ from francofusco/tree_inv_dyn_solver_rne
* Removed std::to_string
* Cast to uint in comparison test
* Merge pull request `#187 <https://github.com/ros2/orocos_kinematics_dynamics/issues/187>`_ from orocos/fix/warnings
* Merge pull request `#171 <https://github.com/ros2/orocos_kinematics_dynamics/issues/171>`_ from craigirobot/upstream-master-chain-forward-dynamics
* Merge pull request `#188 <https://github.com/ros2/orocos_kinematics_dynamics/issues/188>`_ from luzpaz/follow-up-typo-whitespace-fixes
* Merge pull request `#186 <https://github.com/ros2/orocos_kinematics_dynamics/issues/186>`_ from orocos/fix/std-isnan
* scoped_ptr: add missing newline at end of file
* Misc. source comment typo and whitespace fixes
* Merge pull request `#184 <https://github.com/ros2/orocos_kinematics_dynamics/issues/184>`_ from luzpaz/misc-typos
* miscellaneous warning fixes
* utilities: replace deprecated auto_ptr with a basic smart pointer scoped_ptr (supports C++98)
* fix build for missing isnan definition in newer compilers
* fix LDL solver test (copy-paste error)
* Add LDL solver test
* Add FD solver tests
* Implement LDL solver for finding joint acceleration
* Generate forward dynamics solver for chain based on recursive Newton-Euler Method
* Misc doxy and source comment typo fixes
* Edit test
* Using stringstream
* Added #include<string>
* Added #include<stdexcept>
* Merge pull request `#179 <https://github.com/ros2/orocos_kinematics_dynamics/issues/179>`_ from orocos/revert-178-fix/path_circle_memory_leak
* Revert "Add private constructor for delegating initialization. Fixes `#177 <https://github.com/ros2/orocos_kinematics_dynamics/issues/177>`_."
* Merge pull request `#178 <https://github.com/ros2/orocos_kinematics_dynamics/issues/178>`_ from martiniil/fix/path_circle_memory_leak
* Add private constructor for delegating initialization. Fixes `#177 <https://github.com/ros2/orocos_kinematics_dynamics/issues/177>`_.
* Newton-Euler inverse dynamics for trees (fixed missing gravity in test)
* Recursive Newton-Euler inverse dynamics for trees
* Function tree2str improves readability when printing trees on screen
* Tree: added method to extract subtrees
* Merge pull request `#164 <https://github.com/ros2/orocos_kinematics_dynamics/issues/164>`_ from ahoarau/fix/jnttojacdot_typos
* Merge pull request `#155 <https://github.com/ros2/orocos_kinematics_dynamics/issues/155>`_ from craigirobot/upstream-master-add-joint-inertia-dynamics
* Merge pull request `#163 <https://github.com/ros2/orocos_kinematics_dynamics/issues/163>`_ from luzpaz/trivial-typos
* Followup typo
* ChainIdSolver_RNE: add joint inertial torque
* ChainDynParam:  add joint inertia to diagonal elements of joint space inertia matrix
* Joint:  add function to Joint Class to get joint inertia
* few more typos
* fix test typo
* fix typos
* trivial typo fixes
* Merge pull request `#151 <https://github.com/ros2/orocos_kinematics_dynamics/issues/151>`_ from zchen24/fix/velocityprofile_dirac-does-not-stop
* Updated VelocityProfile_Dirac to return p1 when t=0 and time <= 0
* Added velocityprofile_dirac unittest
* Merge pull request `#149 <https://github.com/ros2/orocos_kinematics_dynamics/issues/149>`_ from morxa/jacobiandottest-failure-tolerance
* Fixed velocityprofile_dirac does not stop bug and replaced tab with 4 spaces
* Increase threshold tolerance in jacobiandottest
* Merge pull request `#144 <https://github.com/ros2/orocos_kinematics_dynamics/issues/144>`_ from zchen24/fix/minor-replace-tab-with-spaces
* Minor: replace tab with spaces in chainiksolvervel_wdls
* Merge pull request `#140 <https://github.com/ros2/orocos_kinematics_dynamics/issues/140>`_ from ahoarau/fix/path_rounding_errors
* Merge pull request `#139 <https://github.com/ros2/orocos_kinematics_dynamics/issues/139>`_ from craigirobot/upstream-master-getrotangle-improper-rotation-bug
* Merge pull request `#142 <https://github.com/ros2/orocos_kinematics_dynamics/issues/142>`_ from luzpaz/typos
* Misc. trivial typos
* KDL Frames: Added Improper Rotation test for GetRotAngle
* KDL frames:  removed unnecessary epsilon checks in GetRotAngle singular case
* clamp the value sent to acos to be in bounds
* Merge pull request `#63 <https://github.com/ros2/orocos_kinematics_dynamics/issues/63>`_ from orocos/feature/solvers_use_reference_of_chain
* Add missing virtual function
* Merge remote-tracking branch 'origin/master' into feature/solvers_use_reference_of_chain
* Merge pull request `#122 <https://github.com/ros2/orocos_kinematics_dynamics/issues/122>`_ from pdima/vector2_norm_fix
* Merge pull request `#131 <https://github.com/ros2/orocos_kinematics_dynamics/issues/131>`_ from zchen24/feature/added-chainiksolvervel-pinv-nso-getter-functions
* Merge pull request `#135 <https://github.com/ros2/orocos_kinematics_dynamics/issues/135>`_ from luzpaz/typos
* More trivial typos
* Merge pull request `#133 <https://github.com/ros2/orocos_kinematics_dynamics/issues/133>`_ from luzpaz/typo-fix-cont
* Trivial typo fixes
* Added q_min and q_max size mismatch check in ChainIkSolverPos_NR_JL
* Added weights/opt-pos/alpha getter functions in ChainIkSolverVel_pinv_nso
* Merge pull request `#127 <https://github.com/ros2/orocos_kinematics_dynamics/issues/127>`_ from luzpaz/more-misc-typos
* More typos
* Merge pull request `#121 <https://github.com/ros2/orocos_kinematics_dynamics/issues/121>`_ from luzpaz/doxy-typos
* Fixed Vector2::Norm()
* Typos: doxygen
* Merge pull request `#118 <https://github.com/ros2/orocos_kinematics_dynamics/issues/118>`_ from Intermodalics/fix/const_operators
* Add Frame2 const operator*
* Merge pull request `#114 <https://github.com/ros2/orocos_kinematics_dynamics/issues/114>`_ from craigirobot/add-getsigma-to-wdls-2
* Merge branch 'smart-robotics-fix/non-orthogonal-getrot'
* fix: GetRotAngle no longer causes NaNs on slightly non-orthogonal rotation matrices
* tests: added test for GetRotAngle on slightly non-orthogonal matrices
* Merge pull request `#117 <https://github.com/ros2/orocos_kinematics_dynamics/issues/117>`_ from orocos/fix/get-rot-angle-nans
* Add edge testcase for GetRotAngle
* Added a get function to read the singular values, sigma, so that the manipulability can be calculated from the product.
* Merge pull request `#113 <https://github.com/ros2/orocos_kinematics_dynamics/issues/113>`_ from orocos/serge-nikulin-108
* Check buffer size, fix strncpy
* Merge pull request `#111 <https://github.com/ros2/orocos_kinematics_dynamics/issues/111>`_ from luzpaz/fixed-treshold-typo
* Merge pull request `#110 <https://github.com/ros2/orocos_kinematics_dynamics/issues/110>`_ from luzpaz/trivial-typos
* Merge pull request `#109 <https://github.com/ros2/orocos_kinematics_dynamics/issues/109>`_ from smart-robotics/master
* Merge pull request `#105 <https://github.com/ros2/orocos_kinematics_dynamics/issues/105>`_ from ipa-pgt/patch-1
* Merge pull request `#100 <https://github.com/ros2/orocos_kinematics_dynamics/issues/100>`_ from orocos/fix-99
* fixed thresshold param typo
* Trivial typo fixes
* fix(): Orocos tests additions
* fix(): make arbitrary axis the same as for orocos convention
* fix(): disable tests in CMakeLists.txt
* fix(GetRotAngle): New GetRotAngle function to prevent erros of some flipping
* Make SetToZero usable for Jacobian
* orocos_kdl: install cmake config to share/orocos_kdl/cmake (fix `#99 <https://github.com/ros2/orocos_kinematics_dynamics/issues/99>`_)
* Merge branch 'master' into feature/solvers_use_reference_of_chain
* fix jnttojacdotsolver and add tests
* bumping minor version as this is not ABI compatible
* add changing chain tests for dynamics solvers
* solvers: make solvers use chain references
* segment: add function to change the segment link frame
* chain: add a non-const reference version of getSegment
* solvers: deploy solvers return value infrastructure
* Contributors: Antoine Hoarau, Craig Carignan, Daniel Claes, Dmytro Poplavskiy, Francisco Almeida, Franco Fusco, Ivan Santiago Paunovic, Johannes Meyer, Marieke Copejans, Markus Vieth, Ruben Smits, Serge Nikulin, Shane Loretz, Sjoerd van den Dries, Till Hofmann, Unknown, Xianchao, Zihan Chen, ccarigna, imartini, ipa-pgt, luz.paz

3.2.1 (2019-11-13)
------------------
* Add cxx standard to orocos_kdl CMakeLists.txt (`#12 <https://github.com/ros2/orocos_kinematics_dynamics/issues/12>`_)
* Contributors: Chui Vanfleet

3.2.0 (2019-04-13)
------------------
* Change usage of auto_ptr to unique_ptr, since auto_ptr has been deprecated
* Contributors: Emerson Knapp

3.1.0 (2018-11-20)
------------------
* Update maintainers. (`#9 <https://github.com/ros2/orocos_kinematics_dynamics/issues/9>`_)
* Contributors: Steven! Ragnarök

3.0.1 (2018-06-28)
------------------
* Update maintainers. (`#7 <https://github.com/ros2/orocos_kinematics_dynamics/issues/7>`_)
* Contributors: Steven! Ragnarök

3.0.0 (2018-06-15)
------------------
* ignore deprecation warnings on linux (`#5 <https://github.com/ros2/orocos_kinematics_dynamics/issues/5>`_)
* Contributors: Mikael Arguedas

1.4.0 (2017-12-08)
------------------
* Merge pull request `#3 <https://github.com/ros2/orocos_kinematics_dynamics/issues/3>`_ from ros2/merge_upstream
* Merge remote-tracking branch 'upstream/master' into merge_upstream
* Merge pull request `#107 <https://github.com/ros2/orocos_kinematics_dynamics/issues/107>`_ from dirk-thomas/patch-1
* Merge pull request `#2 <https://github.com/ros2/orocos_kinematics_dynamics/issues/2>`_ from ros2/message_stdout
* avoiding printing status messages to stderr
* avoiding printing status messages to stderr
* Use standard rosdep keyname for Eigen3 dependency. (`#1 <https://github.com/ros2/orocos_kinematics_dynamics/issues/1>`_)
* Restore found Eigen3 variable to previous name.
* disable w4 compiler warnings
* Use the conventional variable for package include directory
* use new choco package for eigen
* find eigen3 on all platforms
* disbale msvc compiler warnings
* correct include dirs for eigen3
* Merge branch 'ros2' of https://github.com/ros2/orocos_kinematics_dynamics into ros2
* look for Eigen3
* Use get_filename_component to normalize paths for Windows
* cleanup package.xml
* inital ros2 migration
* Merge pull request `#93 <https://github.com/ros2/orocos_kinematics_dynamics/issues/93>`_ from orocos/fix/rpath-warning-on-osx
* Enable RPATH for OSX for cmake >= 2.8.12 by default
* Merge pull request `#62 <https://github.com/ros2/orocos_kinematics_dynamics/issues/62>`_ from orocos/fix/make_solvers_use_error_flags
* bumping minor version as this is not ABI compatible
* remove leftover from PR split
* Merge pull request `#83 <https://github.com/ros2/orocos_kinematics_dynamics/issues/83>`_ from orocos/cherry-picked-fixes-for-1.3
* solvers: deploy solvers return value infrastructure
* Fixes `#82 <https://github.com/ros2/orocos_kinematics_dynamics/issues/82>`_: bump version number to latest release
* Make orocos_kdl installspace relocatable.
* Fix config when Eigen_INCLUDE_DIR includes a space
* orocos_kdl: Support getting eps from WDLS velocity solver
* rename double include protection define
* use conservative resize and init the values the same way as the constructor
* tests: be more relaxed on calculated double values. Fixes `#54 <https://github.com/ros2/orocos_kinematics_dynamics/issues/54>`_
* Add missing assign for duration member variable
* solvers: Fix SolverI::strError to work for all defined values
* Merge commit 'refs/pull/39/head' of github.com:orocos/orocos_kinematics_dynamics into release-1.3
* Merge commit 'refs/pull/37/head' of github.com:orocos/orocos_kinematics_dynamics into release-1.3
* Merge commit 'refs/pull/45/head' of github.com:orocos/orocos_kinematics_dynamics into release-1.3
* Fixes `#82 <https://github.com/ros2/orocos_kinematics_dynamics/issues/82>`_: bump version number to latest release
* Merge pull request `#81 <https://github.com/ros2/orocos_kinematics_dynamics/issues/81>`_ from mvistein/master
* support for Visual Studio 2015 C++ compiler
* Merge pull request `#70 <https://github.com/ros2/orocos_kinematics_dynamics/issues/70>`_ from mikepurvis/relocatable
* Merge pull request `#66 <https://github.com/ros2/orocos_kinematics_dynamics/issues/66>`_ from traversaro/patch-4
* Merge pull request `#76 <https://github.com/ros2/orocos_kinematics_dynamics/issues/76>`_ from wannesvanloock/feature/jdot_solver
* Remove Skew comments
* Style changes and minor fixes
* Merge pull request `#71 <https://github.com/ros2/orocos_kinematics_dynamics/issues/71>`_ from snrkiwi/support-getting-eps-from-wdls-solver
* orocos_kdl: Support getting eps from WDLS velocity solver
* Make orocos_kdl installspace relocatable.
* Fix config when Eigen_INCLUDE_DIR includes a space
* fix test compilation on travis
* fix unsigned int warning
* add tests for the 3 representations
* add jdot solver from kuka-isir/rtt_ros_kdl_tools
* Merge pull request `#61 <https://github.com/ros2/orocos_kinematics_dynamics/issues/61>`_ from ahoarau/fix_ret_all_segs_frames
* add fk and fk vel ret vector tests
* fix computation
* Merge pull request `#58 <https://github.com/ros2/orocos_kinematics_dynamics/issues/58>`_ from ahoarau/fk_solvers_all_seg_frames_ret
  Add possibility to return all the FK frames in a vector
* returning -1 if vector size is != segmentNr
* use eigen aligned allocator for std vectors of structures containing fixed size eigen matrices, see http://eigen.tuxfamily.org/dox-devel/group__TopicStlContainers.html for more info
* rename double include protection define
* use conservative resize and init the values the same way as the constructor
* init vector only if size is ok
* Add possibility to return all the FK frames in a vector
* tests: be more relaxed on calculated double values. Fixes `#54 <https://github.com/ros2/orocos_kinematics_dynamics/issues/54>`_
* Add missing assign for duration member variable
* Merge pull request `#55 <https://github.com/ros2/orocos_kinematics_dynamics/issues/55>`_ from rethink-forrest/pinv_nos
* Merge pull request `#39 <https://github.com/ros2/orocos_kinematics_dynamics/issues/39>`_ from rethink-forrest/master
* Prevent memory access past end of twist vector.
* Removed iostream include
* Added check in IK solver for division by zero.
* Updated velocityprofile_traphalf header
* Merge pull request `#50 <https://github.com/ros2/orocos_kinematics_dynamics/issues/50>`_ from rethink-forrest/pinv_nos
* Fixed Nullspace-optimized velocity IK solver.
* Merge pull request `#47 <https://github.com/ros2/orocos_kinematics_dynamics/issues/47>`_ from snrkiwi/rdt-use-solveri-interface-for-idsolvers
* solvers: Ensure ChainIDSolver classes correctly store error codes
* solvers: Use SolverI interface for chainikdsolvers
* solvers: Fix SolverI::strError to work for all defined values
* Merge pull request `#37 <https://github.com/ros2/orocos_kinematics_dynamics/issues/37>`_ from francesco-romano/master
* Merge pull request `#45 <https://github.com/ros2/orocos_kinematics_dynamics/issues/45>`_ from jhu-lcsr-forks/errorstack-double-free
* Making KDL errorstack static (prevents 'double-free or corruption' on exit)
* Updated RPATH support
* Check that the maxvel is obtainable in a half trapezoidal velocity profile.
* Added support to RPATH for CMake >= 2.8.12
* Contributors: Antoine Hoarau, Dirk Thomas, Forrest Rogers-Marcovitz, Francesco Romano, Jonathan Bohren, Karsten Knese, Michael Vistein, Mike Purvis, Ruben Smits, Silvio Traversaro, Stephen Roderick, Steven! Ragnarök, Wannes Van Loock

1.3.1 (2016-04-05 11:45:20 +0200)
---------------------------------
* 1.3.1
* Merge pull request `#29 <https://github.com/ros2/orocos_kinematics_dynamics/issues/29>`_ from traversaro/patch-3
* Merge pull request `#31 <https://github.com/ros2/orocos_kinematics_dynamics/issues/31>`_ from MrMagne/master
* Merge pull request `#32 <https://github.com/ros2/orocos_kinematics_dynamics/issues/32>`_ from rethink-kmaroney/master
* Fixes GetQuaternion non-zero matrix trace check
* same order for paramters in docs and code
* make doxygen happy
* orocos_kdl: explicity declare friend functions outside the classes
* Get updated FindEigen3.cmake from Eigen repository
* Use the FindEigen3.cmake from the Eigen repository
* Contributors: Charles Prévot, Kyle Maroney, Ruben Smits, Silvio Traversaro

1.3.0 (2014-07-15 11:10:41 +0200)
---------------------------------
* Releasing 1.3.0
* orocos_kdl: remove the divide by 1000 since it's not agnostic wrt units. Fixes `#28 <https://github.com/ros2/orocos_kinematics_dynamics/issues/28>`_
* Merge pull request `#27 <https://github.com/ros2/orocos_kinematics_dynamics/issues/27>`_ from snrkiwi/fix-wdls
* Merge pull request `#25 <https://github.com/ros2/orocos_kinematics_dynamics/issues/25>`_ from jhu-lcsr-forks/master
* solvers: Add lambda_scaled computation check for sigmaMin in WDLS
* Merge pull request `#26 <https://github.com/ros2/orocos_kinematics_dynamics/issues/26>`_ from snrkiwi/expand-solveri
* solvers: Fix chainjnttojacsolver to use solver interface
* resolve merge conflict
* Adding metapackage
* solvers: replace static const by enum, as defining and assigning static consts in a header is not safe.
* fix numerous compiler warnings
* drop Eigen2 support since it will be deprecated in Eigen 3.3
* tests: allow degraded solutions in the test
* Merge pull request `#24 <https://github.com/ros2/orocos_kinematics_dynamics/issues/24>`_ from snrkiwi/fixes
* cmake: Silence Eigen >= 3.2.0 warnings about deprecated Eigen2
* kdl: fix toggling of left-right solving for the SVD calculation
* solvers: Correctly return degraded error code if child solver indicates degraded solution in IKSolverVel_NR
* solvers: Modify ChainJntToJacSolver to support calculating Jacobian in intermediate frames
* solvers: Support changing internal parameters after construction of IKSolverVel_WDLS
* solvers: Add missing return
* solvers: Update documentation and add degraded and undefined error codes to solver interface
* velocityprofile: Support trap. velocity profile with velocity specification
* Merge pull request `#22 <https://github.com/ros2/orocos_kinematics_dynamics/issues/22>`_ from francesco-romano/master
* Added Boost header path to KDL_INCLUDE_DIRS variable so that it is correctly exported for other libraries using kdl.
* cmake: add support for LIB_SUFFIX cmake flag
* Merge pull request `#19 <https://github.com/ros2/orocos_kinematics_dynamics/issues/19>`_ from jensenb/fixFriendFunctions
* Correct friend function declarations with default arguments
* Merge pull request `#18 <https://github.com/ros2/orocos_kinematics_dynamics/issues/18>`_ from snrkiwi/cmake-fixes
* cmake: Add pkgconfig DIR to output config file
* cmake: Correct typo's in CMake output config file
* Fix some CMake deps for the tests, examples and models
* Merge branch 'stl_cont_fix'
* Fix for systems that don't allow definitions of stl containers with incomplete types
* Make source version higher than released/package version
* Merge pull request `#17 <https://github.com/ros2/orocos_kinematics_dynamics/issues/17>`_ from jensenb/versionFix
* Bump version in CMakeLists.txt to 1.2.2
* Contributors: Brian Jensen, Jonathan Bohren, Ruben Smits, Stephen Roderick, francesco-romano

1.2.2 (2014-02-17)
------------------
* "1.2.2"
* Merge pull request `#15 <https://github.com/ros2/orocos_kinematics_dynamics/issues/15>`_ from jf---/jf/pykdl_fixes
* the default constructor alpha value for ChainIkSolverVel_pinv_nso is 0.25, while that type is an int. not 100% sure, but assuming that type should be a double and that the default value is correct
* Merge branch 'patch-2' of http://github.com/traversaro/orocos_kinematics_dynamics
* Merge pull request `#14 <https://github.com/ros2/orocos_kinematics_dynamics/issues/14>`_ from spencerjackson/master
* Add url to ROS wiki in package.xml
* Revert "Moving configs from bloom branch"
* Moving configs from bloom branch
* Added out of the box basic Windows support
* Contributors: Jelle Feringa, Ruben Smits, Silvio Traversaro, Spencer Jackson

1.2.1 (2013-12-09)
------------------
* 1.2.1 release
* Contributors: Ruben Smits

1.2.0 (2013-12-03)
------------------
* Releasing 1.2.0
* Fixes `#8 <https://github.com/ros2/orocos_kinematics_dynamics/issues/8>`_: Error in documentation Rotation::RPY
* cmake: add missing cmake config version file
* cmake: add files that were lost in the cmake changes
* cmake: rewrite of the cmake config file
* experimental: move into separate branch, merge back when compiling
* Merge remote-tracking branch 'snrkiwi/use-versalemma-for-getrotangle'
* Revert "fix `#1036 <https://github.com/ros2/orocos_kinematics_dynamics/issues/1036>`_: implemented more robust version of GetRotAngle, it uses a conversion to quaternions under the hood"
* frames: Implement more robust GetRotAngle() using Versa-Lemma approach
* Merge branch 'fix-wdls-solver-error-logic' of https://github.com/snrkiwi/orocos-kdl into fix-wdls-solver-error-logic
* Merge branch 'fix-pinv-solver-error-logic' of https://github.com/snrkiwi/orocos-kdl into fix-pinv-solver-error-logic
* Merge branch 'fix1044-solver-error-logic'
* Merge remote-tracking branch 'origin/bloom' into fix1044-solver-error-logic
* Merge remote-tracking branch 'origin/bloom'
* tests: Add unit test for WDLS solver
* tests:Add fully singular case to singular value test
* vel_wdls: Added lambda scaling to wdls chainiksolvervel
* tests: Update return codes for singular value test
* vel_wdls: Return data on jacobian singular value conditioning
* vel_pinv: Provide access to number of near zero sigma values.
* Modify chainiksolvervel_wdls error processing logic to use solver interface
* svd_eigen_HH: Return error codes instead of assert'ing on error
* Ensure all FK and IK solvers have derived from the solver interface class
* Modify chainiksolvervel_pinv error processing logic to use solver interface
* Add solver interface supporting error codes and storage of the last error
* tests: Add unit test for singular values using psuedo inverse solver
* Modify chainiksolverpos_nr error processing logic to use solver interface
* config: Look for eigen3 in MacPorts install also
* tests: Use constant value for variable-sized array of non-POD elements
* Fixing repeated include directory concatenation from cache variable in FindEigen3.cmake
* fix `#1036 <https://github.com/ros2/orocos_kinematics_dynamics/issues/1036>`_: implemented more robust version of GetRotAngle, it uses a conversion to quaternions under the hood
* use doubles instead of floats for quaternion calculation
* cmake: tests should not end up in bin dir
* fix `#1036 <https://github.com/ros2/orocos_kinematics_dynamics/issues/1036>`_: add Eigen include directory to the exported cflags
* Fix `#1035 <https://github.com/ros2/orocos_kinematics_dynamics/issues/1035>`_: Do not override the pkgconfig path, append instead
* Fix for bug `#1006 <https://github.com/ros2/orocos_kinematics_dynamics/issues/1006>`_: Jacobian: missing EIGEN_MAKE_ALIGNED_OPERATOR_NEW
* Contributors: Jonathan Bohren, Ruben Smits, Stephen Roderick

1.1.102 (2013-04-18)
--------------------
* clean up dependencies
* use consistend naming scheme
* Contributors: Ruben Smits

1.1.101 (2013-04-17 16:55)
--------------------------

1.1.100 (2013-04-17 15:12)
--------------------------
* 1.1.99-1
* Contributors: Ruben Smits

1.1.99 (2013-04-17 13:53)
-------------------------
* prepare for release with bloom
* Fix for bug 1026 - VelocityProfile_TrapHalf moves backwards after setting duration
* tests: add unittest for velocityprofiles, related to bug `#1026 <https://github.com/ros2/orocos_kinematics_dynamics/issues/1026>`_
* pkgconfig: generate orocos_kdl.pc file next to orocos-kdl.pc, which will be deprecated soon
* Minor fixes to convenience nmake / MSVC compiler (missing return values, missing define)
* Fixed operator <<(std::ostream& os, const Tree& tree)
* Fixed the memory alloc/dealloc problem of bug 973.
* Added some comment to the svd_eigen_Macie routine.
* Added a way to identify the underlying object when using Path* objects.
* Still correcting the build system.
* Corrected build system.
* Improved documentation.
* Corrected and improved documentation:
* Added documentation to svd_eigen_Macie.hpp
* Removed methods added  by the commit of Gianni.
* Merge branch 'master' of https://git.mech.kuleuven.be/robotics/orocos_kinematics_dynamics
* added the functions NumberOfSubPaths and SubPathLength to Path_Composite and Path_RoundedComposite
* Adaptations to the build system for the examples.
* Added some introspection methods to Path_Composite and Path_RoundedComposite.
* Improvement on the Euler angles and yaw-pitch-roll routines.
* Added a new inverse position kinematics solver.
* Added some matlab/octave files to visualise the output of trajectory_example.cpp
* Fix for Bug 957: no example for traj. generation.
* Fix for Path_RoundedComposite.
* Added a CMake build file for the examples.
* Added a few notes to the unit tests of S. Roderick.
* Bug 947 more comprehensive tests of angle-axis conversion
* clarified the unit tests of S. Roderick by explicity using the transformation.
* Bug 947 add test cases for diff function
* Improved on documentation of diff() and addDelta() functions.
* Changed Doxyfile.in to use MathJax.
* Changed the documentation of the single axis rotational interpolator.
* Bug (947) changed meaning of epsilon parameter
* Add Unit test for bug `#947 <https://github.com/ros2/orocos_kinematics_dynamics/issues/947>`_
* Bug 947 repaired GetRot() and GetRotAngle()
* added in source docs in vereshchagin's solver. Also a test example is added to solvertest
* kdl: Fix for Bug `#931 <https://github.com/ros2/orocos_kinematics_dynamics/issues/931>`_: IFNDEF header guard for pinv_nso matches that of pinv preventing simultaneous include
* kdl: fix declaration of Equal operator for Rotations
* solvers: removed asserts from treeiksolverpos_online
* added tree ik solverpos that enforces cartesian and joint maximal velocities
* kdl: output more data about joint and segment
* fix for bug `#924 <https://github.com/ros2/orocos_kinematics_dynamics/issues/924>`_: install_name_tool path is not getting set correctly, applied patch provided by William Woodall
* added vereshchagin ID solver with corrections to original from Ruben
* Closes Bug 906: Building orocos_kinematics_dynamics in ROS on Mac OS X
* cmake: let find_package for eigen3 fail silently
* cmake: fall back on own cmake module if the system does not provide a module for eigen3
* Revert "cmake: replace own written eigen cmake module by the provided module by libeigen3-dev"
* manifest: add rosdep for eigen
* add Spline velocity profile, thanks to Konrad Banachowicz
* orocos_kdl: add missing return in case of success for the CartToJnt function
* kdl: remove unneeded assert in svd_eigen_HH
* Merge branch 'experimental'
* manifest: add pkg-config dependency and use it to get the eigen flags in the manifest
* cmake: replace own written eigen cmake module by the provided module by libeigen3-dev
* cmake: replace own written eigen cmake module by the provided module by libeigen3-dev
* Merge branch 'experimental' of https://kforge.ros.org/geometry/kdlclone into experimental
* move installation from install to install_dir to avoid conflicing name with INSTALL on osx
* add dependency on eigen stack to export include flags
* eigen: replace eigen2 with eigen3 dependency
* Merging eigen3 branch into experimental
* Restore Makefile again
* eigen is not part of the geometry stack any more, it has its own stack now
* Replace cast to double* with const. Add cmake macro to find eigen3
* Restore Makefile
* Replace cast to double* with const. Add cmake macro to find eigen3
* cpp: replace eigen package with eigen rosdep
* orocos_kdl: fix Bug 778 - Documentation of getChain out of date
* kdl: Fix Makefile to force local installation
* kdl: make library location the same for -L and rpath
* orocos_kdl: clean up after extraction of python bindings
* PyKDL: create separate package for python bindings
* kdl: fix for bug 701: cppunit needs to link against libdl (at least on some distros), applied patch provided by Morgan Quigley
* kdl: Fix Makefile to force local installation
* kdl: make library location the same for -L and rpath
* orocos_kdl: clean up after extraction of python bindings
* PyKDL: create separate package for python bindings
* eigen3: fix copying from/into symmetric matrices
* cmake: add definition for eigen2 support to make it work with eigen3
* Merge remote branch 'origin/master' into eigen3
* rename kdl to orocos_kdl
* Contributors: Azamat Shakhimardanov, Erwin Aertbelien, Gianni Borghesan, Markus Neuner, Ruben Smits, Stephen Roderick, Steven Bellens, Wim Meeussen, WouterBancken
