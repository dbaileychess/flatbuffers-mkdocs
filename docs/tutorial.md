# Tutorial

This tutorial provides a basic example of how to work with FlatBuffers.

=== "C++"

    ```c
    flatbuffers::FlatBufferBuilder builder(1024);
    ```

=== "C#"

    ```c#
    var builder = new FlatBufferBuilder(1024);
    ```

Some other text

=== "C++"

    ```c
    auto weapon_one_name = builder.CreateString("Sword");
    ```

=== "C#"

    ```c#
    var weaponOneName = builder.CreateString("Sword");
    ```

   