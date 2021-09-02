# Chat

A Chat app using GenServer to show how processes work and if the process dies it is resarted again 

## How to use the app:
  - run the `iex -S mix`  command from the terminal in the current project directory.
  - to the pid run the following command `{:ok, pid} = Chat.Server.start_link` 
  - the above command also starts the chat server
  - to check if there a messages run `Chat.Server.get_msgs(pid)` command.
  - if it return an empty object you can add message using `Chat.server.add_msg("Hello from Elixir")`

![image](https://user-images.githubusercontent.com/54530122/131801327-3fc55f7f-6989-4222-810f-4a8b34c7ae40.png)


