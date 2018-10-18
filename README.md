# Gradle probes
- Run `brew install gradle` to install Gradle
- Run `gradle -v` to check that it is installed
- `cd` to repo root folder
- Run `gradle hello` to see the hello-world task execution results

# See all available tasks
Run `gradle tasks --all`

# Run multiple tasks
Run `gradle hello dependentTask1`

# Run task by alias (abbreviation)
Run `gradle pNN` // alias for printNickName

# Run the task with daemon option
Run `gradle hello --daemon`