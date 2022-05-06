# ZVPN - A wrapper shell over open-vpn3

The shell is a wrapper shell over open-vpn3. It will help users to easily connect open vpn profiles.


# Usage
- Copy the methods to `~/.<shell>rc` file or common shell file which may be sourced in rc or profile file.
- Use `zvpn` -> `help` for all available options


# Available functions
- Available commands (mandatory attributes are marked with *): 
 - start           - Starts a vpn profile. Usage: zvpn <profile name> -> select option 2 
 - status          - Status of a vpn profile. Usage: zvpn <profile name> -> select option 3 
 - restart         - Restart a vpn profile. Usage: zvpn <profile name> -> select option 4 
 - stop            - Stop a vpn profile. Usage: zvpn <profile name> -> select option 5 
 - stats           - Statistics of a vpn profile. Usage: zvpn <profile name> -> select option 6 
 - config-import   - Import a ovpn config. Usage: zvpn <Location of ovpn file> <profile name> -> select option 7 
 - config-list     - List all imported config. Usage: zvpn -> select option 8 
 - config-delete   - Delete imported config Usage: zvpn <profile name> -> select option 9 
 - help            - Help. Usage: zvpn -> select option 10