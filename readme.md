# Elixir Tests

https://elixir-lang.org/

"The only prerequisite for Elixir is Erlang."

### Instalando no Windows

Você precisará do [chocolatey](https://chocolatey.org/install).

Abra o powershell como administrador e execute a linha que é pedida,
algo que começa com `Set-ExecutionPolicy Bypass -Scope Process...`.

Aind no terminal como administrador, exeute:

    cinst elixir

Eu obtive:

    Chocolatey v0.10.15
    Installing the following packages:
    elixir
    By installing you accept licenses for the packages.
    Progress: Downloading erlang 22.3... 100%
    Progress: Downloading Elixir 1.10.3... 100%

    erlang v22.3 [Approved]
    erlang package files install completed. Performing other installation steps.
    The package erlang wants to run 'chocolateyInstall.ps1'.
    Note: If you don't run this script, the installation will fail.
    Note: To confirm automatically next time, use '-y' or consider:
    choco feature enable -n allowGlobalConfirmation
    Do you want to run the script?([Y]es/[A]ll - yes to all/[N]o/[P]rint): y

    Downloading erlang 64 bit
    from 'https://www.erlang.org/download/otp_win64_22.3.exe'
    Progress: 2% - Saving 2.02 MB of 90.6 MB

    ...
    ...
    ...

    Downloading Elixir
    from 'https://github.com/elixir-lang/elixir/releases/download/v1.10.3/Precompiled.zip'
    Progress: 100% - Completed download of C:\Users\flavi\AppData\Local\Temp\chocolatey\Elixir\1.10.3\Precompiled.zip (5.42 MB).
    Download of Precompiled.zip (5.42 MB) completed.
    Hashes match.
    Extracting C:\Users\flavi\AppData\Local\Temp\chocolatey\Elixir\1.10.3\Precompiled.zip to C:\ProgramData\chocolatey\lib\Elixir...
    C:\ProgramData\chocolatey\lib\Elixir
    The Elixir commands have been added to your path.

    Please restart your current shell session to access Elixir commands:
    elixir
    elixirc
    mix
    iex.bat
    Environment Vars (like PATH) have changed. Close/reopen your shell to
    see the changes (or in powershell/cmd.exe just type `refreshenv`).
    The install of elixir was successful.
    Software installed to 'C:\ProgramData\chocolatey\lib\Elixir'

    Chocolatey installed 2/2 packages.
    See the log for details (C:\ProgramData\chocolatey\logs\chocolatey.log).


### Checking the installed version of Elixir

    elixir --version.

    Erlang/OTP 22 [erts-10.7] [64-bit] [smp:8:8] [ds:8:8:10] [async-threads:1]
    Elixir 1.10.3 (compiled with Erlang/OTP 21)


### Docker

Experimente começar com docker


### Getting Started

https://elixir-lang.org/getting-started/introduction.html
