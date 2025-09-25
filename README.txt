IMPORTANT: .NET 8.0 Installation Required

This library requires Microsoft .NET 8.0 Runtime or SDK to be installed on your system before usage.

Why is .NET 8.0 needed?

.NET 8.0 is the latest major release of the .NET platform by Microsoft, bringing important performance improvements,
security updates, and new APIs that this library depends on.

Running this library without the proper .NET 8.0 runtime will result in errors or the application failing to start.

How to install .NET 8.0

1. Visit the official Microsoft download page for .NET 8.0:
   https://dotnet.microsoft.com/download/dotnet/8.0

2. Choose the appropriate installer for your operating system:
   - Windows x64 / x86
   - Linux (various distros)
   - macOS

3. For running existing apps only, download the .NET 8.0 Runtime.
   If you plan to develop or build from source, download the .NET 8.0 SDK.

4. Follow the installation instructions specific to your platform.

5. After installation, open a command prompt or terminal and verify the installation by running:
   dotnet --version
   You should see output starting with “8.0”.

Additional Notes

- Make sure any environment variables or system PATHs are updated accordingly during installation.
- If you are deploying on servers or CI environments, ensure that .NET 8.0 runtime is included in your deployment packages.
- For more detailed guidance, visit the official Microsoft documentation linked above.

Thank you for choosing this library! If you have questions or issues, please check your .NET installation or visit the Microsoft support forums.
