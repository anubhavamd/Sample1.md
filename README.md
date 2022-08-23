</div>

<table 1>
<tr>
<th>Setup Instructions</th>

<th>Syncing-Building-Installing-and-Testing</th>

</tr>
<tr>
<td>
<pre>
<a href="/anubhav_migraphx_exp.md#1-getting-started-guide-for-migraphx-">1. Setting up the development machine </a> 
        <a href="/anubhav_migraphx_exp.md#11-introduction-">1.1. Choice of OS </a> 
	<a href="/anubhav_migraphx_exp.md#subparagraph12">1.2. Get the build dependencies</a>
    <a href="/anubhav_migraphx_exp.md#subparagraph13">1.3. Setup access to the Git and Gerrit repositories</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph111">1.3.1. Check for existing SSH key pairs</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph111">1.3.2. SSH key pair generation</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph111">1.3.3. Create config file</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph111">1.3.4. Verify access to Gerrit</a>
<a href="/anubhav_migraphx_exp.md#1-getting-started-guide-for-migraphx-">2. Verify access to Perforce repositories (optional) </a>
<a href="/anubhav_migraphx_exp.md#1-getting-started-guide-for-migraphx-">3. NFS Setup for the Development Machine </a>
<a href="/anubhav_migraphx_exp.md#1-getting-started-guide-for-migraphx-">4. Setting up the Target machine </a>
	<a href="/anubhav_migraphx_exp.md#subparagraph12">4.1. Configure Grub (optional)</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph12">4.2. Boot into textmode (optional)</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph12">4.3. Add user to video/render group</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph12">4.4. Update PCI IDs</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph12">4.5. BIOS Settings(optional)</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph111">4.5.1. For KV & CZ</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph111">4.5.2. For Raven</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph12">4.6. Additional packages</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph12">4.7. NFS setup for the target machine</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph12">4.8. Vega10</a>
	
</pre>
</td>

<td>
<pre>
<a href="/anubhav_migraphx_exp.md#3-c-user-guide-">1. Setup your development environment</a>
<a href="/anubhav_migraphx_exp.md#3-c-user-guide-"2. Download the source code</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph21"2.1. Download the Git projects from Gerrit</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph21"2.2. Using CI Docker Image to Build ROCm</a>
        <a href="/anubhav_migraphx_exp.md#subparagraph21"2.2.1.	Docker Install and Setup</a>
		<a href="/anubhav_migraphx_exp.md#subparagraph21"2.2.2.	One Time Setup (per user/host)</a>
<a href="/anubhav_migraphx_exp.md#3-c-user-guide-"3. Building the Compute Stack</a>		
	<a href="/anubhav_migraphx_exp.md#subparagraph21"3.1. Setup the environment</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph21"3.2. Running automated build scripts</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph21"3.3. Debugging Docker Container Built Projects with gdb</a>
<a href="/anubhav_migraphx_exp.md#3-c-user-guide-"4. Deploying ROCm on the target device (Optional)</a>	
	<a href="/anubhav_migraphx_exp.md#subparagraph21"4.1. Developer build</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph21"4.2. Release build</a>
<a href="/anubhav_migraphx_exp.md#3-c-user-guide-"5. Installing on the target device</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph21"5.1. Installation</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph21"5.1. Confirming installation</a>
<a href="/anubhav_migraphx_exp.md#3-c-user-guide-"6. Testing the kernel and HSA stack</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph21"6.1. Debugging the Compute Stack</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph21"6.1. Debug logging</a>
</pre>
</td>
</table 1>

