# Hamilton SlackMessenger

Hamilton SlackMessenger is a submethod library that enables Hamilton runs to send one-way status updates to Slack. This facilitates real-time communcation regarding run states, improving monitoring and workflow efficiency

### Features
- **Seamless Integration**: Works within Hamilton methods to send updates to Slack Channels
- **Customisable Updates**: Add Slack notifications at key points in your methods

### Prerequisites 
Before using the library, ensure you have the following:

	Network Access: A stable connection to the internal network drive dna_pipelines.
	Dependencies:
        HslFilDirectoryLib.hsl (installer included)
        HSLGetSerialNumber_WSI.hsl (Repository here)

### Installation

    Download and Place Files:
        Clone this repository or download the files.
        Install the library files into the HAMILTON\Library\WSI directory.

    Verify Library Mapping:
        Open the .smt file associated with your project.
        Ensure all libraries are mapped correctly to avoid runtime errors.

    Save Changes:
        Save the .smt file after mapping.


### Usage

    Import the Library:
        Include the library in your method of choice within the Hamilton IDE.

    Setup Slack Updates:
        Add the Start_Check command during the user input section to initialize Slack messaging.
        Place the Update command at key points in the method to send Slack updates about the method's run state.


### Support

For questions or support, contact Chris Henderson

    Email: ch33@sanger.ac.uk
    GitHub: ChrisH33
