# Example

🎭 Example usage of Swish in Xcode. You can develop in Xcode on macOS and can use an External Build System to deploy your Swift code on Linux.

## Configure Xcode

1. Add a new target and select **External Build System** (in cross-plattform tab) as template.
2. Set `/bin/bash` as the build tool of the target.
3. Select your generated target and set arguments (in info tab) to `swish <username> <hostname>`
4. Build your project (with the newly created target) and enjoy your compiled swift code on your remote machine.

## Run Project

Open a new terminal window and connect to your remote machine via SSH.

```
ssh <username>@<hostname>
```

Navigate to the synced project directory and run your project as usual.

```
cd ~/Swish/<projectname>
.build/debug/<projectname>
```

Have fun 🍻

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
