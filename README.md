# sonar-kotlin

[![build status](https://travis-ci.org/arturbosch/sonar-kotlin.svg?branch=master)](https://travis-ci.org/arturbosch/sonar-kotlin)
[![build status windows](https://ci.appveyor.com/api/projects/status/bn2vto5dnkenxeg5?svg=true
)](https://ci.appveyor.com/project/arturbosch/sonar-kotlin)

![sonar-kotlin-in-action](img/sonar-kotlin.png)

### Features

- Integrates [detekt](https://github.com/arturbosch/detekt) for code analysis
- Default quality profile `Detekt way`
- Syntax highlighting
- Supports SonarQube 5.6 and 6.4

### Usage

Sonar-kotlin is not yet uploaded to the `Update Center`

- `git clone https://github.com/arturbosch/sonar-kotlin`
- `cd sonar-kotlin`
- `./gradlew build`
- `cp build/libs/sonar-kotlin-[enter_version].jar $SONAR_HOME/extensions/plugins`
- `cd $SONAR_HOME/bin/[your_os]`
- `./sonar.sh restart`