# Changelog

## [1.7.2](https://github.com/antmelekhin/ansible-role-java/compare/v1.7.1...v1.7.2) (2024-12-01)


### Documentation

* **README:** updated requirements ([ee69da3](https://github.com/antmelekhin/ansible-role-java/commit/ee69da31e6c68f2e3a02132210daa71dc8bf90b0))

## [1.7.1](https://github.com/antmelekhin/ansible-role-java/compare/v1.7.0...v1.7.1) (2024-10-17)


### Code Refactoring

* fix some variables form `vars/main.yml` file ([2f1d259](https://github.com/antmelekhin/ansible-role-java/commit/2f1d259e771d19dfeb12744d52a132c06a4cd810))

## [1.7.0](https://github.com/antmelekhin/ansible-role-java/compare/v1.6.0...v1.7.0) (2024-10-06)


### Continuous Integration

* use `ubuntu-22.04` instead of `ubuntu-latest` ([1db6cd5](https://github.com/antmelekhin/ansible-role-java/commit/1db6cd5720f8ce938be8e0c0c59404f5262072be))


### Features

* add `java_type` variable ([#9](https://github.com/antmelekhin/ansible-role-java/issues/9)) ([9a8b3cd](https://github.com/antmelekhin/ansible-role-java/commit/9a8b3cdaa87e25e7eab7ae28ed8b61eed5a0e33b))


### Styles

* minor fixes ([884ece5](https://github.com/antmelekhin/ansible-role-java/commit/884ece53a077b4857c00704e3f0b4db2242dda58))

## [1.6.0](https://github.com/antmelekhin/ansible-role-java/compare/v1.5.0...v1.6.0) (2024-08-10)


### Improvements

* merge OS-specific variables into the `vars/main.yml` file ([#8](https://github.com/antmelekhin/ansible-role-java/issues/8)) ([d05d72f](https://github.com/antmelekhin/ansible-role-java/commit/d05d72f545acf7e10de975341cb8a8c1fd70bedc))

## [1.5.0](https://github.com/antmelekhin/ansible-role-java/compare/v1.4.1...v1.5.0) (2024-07-29)


### Features

* add `meta/argument_specs.yml` ([0cdc730](https://github.com/antmelekhin/ansible-role-java/commit/0cdc7301d1bcba08e6d5c66563c45719a48ebd8e))

## [1.4.1](https://github.com/antmelekhin/ansible-role-java/compare/v1.4.0...v1.4.1) (2024-07-27)


### Fixes

* split `vars/main.yml` file by distribution ([#7](https://github.com/antmelekhin/ansible-role-java/issues/7)) ([fae39fc](https://github.com/antmelekhin/ansible-role-java/commit/fae39fcd5ae1358aa87a0b9887ca51425539e106))

## [1.4.0](https://github.com/antmelekhin/ansible-role-java/compare/v1.3.0...v1.4.0) (2024-07-26)


### Features

* add fedora support ([1c4b83a](https://github.com/antmelekhin/ansible-role-java/commit/1c4b83a74069ba0c3e816fa33ab9a1588f3db590))

## [1.3.0](https://github.com/antmelekhin/ansible-role-java/compare/v1.2.0...v1.3.0) (2024-07-25)


### Improvements

* merge OS-specific variables into the main file ([#6](https://github.com/antmelekhin/ansible-role-java/issues/6)) ([d330b37](https://github.com/antmelekhin/ansible-role-java/commit/d330b372dc86392e67436a448c8ffde95650d055))


### Tests

* clean version output in the default scenario ([0910474](https://github.com/antmelekhin/ansible-role-java/commit/09104742edd1f72a644d61717089f519382ca04d))

## [1.2.0](https://github.com/antmelekhin/ansible-role-java/compare/v1.1.0...v1.2.0) (2024-06-10)


### Features

* add corretto java package ([#5](https://github.com/antmelekhin/ansible-role-java/issues/5)) ([17b0573](https://github.com/antmelekhin/ansible-role-java/commit/17b05736abb43cfabe7477b212f623d319ec99c7))


### Styles

* minor changes ([ee3da9c](https://github.com/antmelekhin/ansible-role-java/commit/ee3da9c803c209b4577d230c0de1696bacd524ed))

## [1.1.0](https://github.com/antmelekhin/ansible-role-java/compare/v1.0.4...v1.1.0) (2024-05-24)


### Features

* add `amazonlinux` support and improv common role style ([#4](https://github.com/antmelekhin/ansible-role-java/issues/4)) ([7f9930a](https://github.com/antmelekhin/ansible-role-java/commit/7f9930aa630bbfe90debf7ce886ff2c3b1b1882f))


### Styles

* add newline to end of file ([00a42db](https://github.com/antmelekhin/ansible-role-java/commit/00a42db90c4ec2d3b5a749a4af818e79e9b40421))

## [1.0.4](https://github.com/antmelekhin/ansible-role-java/compare/v1.0.3...v1.0.4) (2024-04-26)


### Documentation

* **README:** fixed examples view for Ansible Galaxy ([2842d2a](https://github.com/antmelekhin/ansible-role-java/commit/2842d2a5db2132d0ba331822a7edb6d5139f5b22))


### Fixes

* fixed running a role in `check_mode` ([4733e8f](https://github.com/antmelekhin/ansible-role-java/commit/4733e8f836a9fa5f292d96ee870e8b22dccca001))


### Styles

* use double underline regiter variable ([6160133](https://github.com/antmelekhin/ansible-role-java/commit/61601339cd7108ede333d560f52fbabfeb9dd577))


### Tests

* add .tox as ignore ([5935e66](https://github.com/antmelekhin/ansible-role-java/commit/5935e6681c06eda34ae9a89810e857b3a1d59f5e))
* add role_name prefix to instance name ([ef4fef3](https://github.com/antmelekhin/ansible-role-java/commit/ef4fef355fc7ba416ee413c0f97a9ba758a3016c))
* run linters in its own workflow ([7ac1c0b](https://github.com/antmelekhin/ansible-role-java/commit/7ac1c0bd2379553055c92c10c2a16496c74c92f5))

## [1.0.3](https://github.com/antmelekhin/ansible-role-java/compare/v1.0.2...v1.0.3) (2024-04-20)


### Code Refactoring

* rm loop for `include_vars` ([bff4770](https://github.com/antmelekhin/ansible-role-java/commit/bff4770431cbdad94d3258316bed25f9a44842f1))


### Continuous Integration

* update release rules ([e64883c](https://github.com/antmelekhin/ansible-role-java/commit/e64883c5c8ee8904e59e0fe53d7d2e40c21bd2ca))
* update workflows ([3ad97db](https://github.com/antmelekhin/ansible-role-java/commit/3ad97db3a04a6cc85df2f97d8973b67a9fb87dc5))


### Styles

* quote strings ([9891ea1](https://github.com/antmelekhin/ansible-role-java/commit/9891ea103966caac3584ca3c3aefcb4485356eb4))

## [1.0.2](https://github.com/antmelekhin/ansible-role-java/compare/v1.0.1...v1.0.2) (2024-03-26)


### Fixes

* add missing become ([#3](https://github.com/antmelekhin/ansible-role-java/issues/3)) ([ffa0692](https://github.com/antmelekhin/ansible-role-java/commit/ffa0692ae4b7057ec4945572b04e631f4c946b0b))


### Styles

* add empty line after ansible comment ([6766872](https://github.com/antmelekhin/ansible-role-java/commit/6766872696d4c0dd69a8428a8ab7055d46c6d231))


### Tests

* **fix:** set `role_name_check` as skip_list ([e6826f2](https://github.com/antmelekhin/ansible-role-java/commit/e6826f219de3c8869c5bb7cd5290642dd48c677f))

## [1.0.1](https://github.com/antmelekhin/ansible-role-java/compare/v1.0.0...v1.0.1) (2024-02-22)


### Code Refactoring

* fix default package ([#2](https://github.com/antmelekhin/ansible-role-java/issues/2)) ([6e28efb](https://github.com/antmelekhin/ansible-role-java/commit/6e28efb7ffe50e48ab9b1de363236a1c25804b06))


### Styles

* rename `include variables` task ([c676e84](https://github.com/antmelekhin/ansible-role-java/commit/c676e84b3d362c8d6d79956c7a0bac558ccabb2a))
* rename some tasks and update description ([#1](https://github.com/antmelekhin/ansible-role-java/issues/1)) ([9dd4431](https://github.com/antmelekhin/ansible-role-java/commit/9dd4431d30f22ec9b3937dbef72859075cac4ca4))

## [1.0.0](https://github.com/antmelekhin/ansible-role-java/compare/...v1.0.0) (2023-11-10)


### Features

* initial commit ([4ffeb9e](https://github.com/antmelekhin/ansible-role-java/commit/4ffeb9e12abc8ffe7f06b115693691895a15516a))
