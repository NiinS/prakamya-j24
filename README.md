<div align="center">

[//]: # (<br>)
  <img src="imgs/green-minimal.png" alt="Prakamya-j24 Linux x86 64 bit JDK/JVM" width="1000" height="auto" />
  <h1>Prakamya-j24</h1>
  <h4>Linux x86 64-bit JVM 24 OpenJDK baseline transformation (VM code and build) via C++20..26 (&higher) language features and standard lib</h4>
<hr/>
</div>

<div>
<details>
<summary>Background</summary>
<p style="font-size:10px;font-family:arial,serif">
Prakamya-j24 is an opinionated (& incrementally transformed) Linux (x86) based 64-bit JVM infused with modern C++ standards (>= C++20..26) 
in the JVM internal code and the build process. This approach allows JVM deployments on 64-bit Linux to benefit from an enhanced C++ feature set, 
performance improvements, and the cutting edge of C++ language design directly within the JVM.
</p>
<p style="font-size:7px;font-family:arial,serif">
Note that standard JVM implementations (e.g. OpenJDK) are based on C++14 (in the JVM code and build process), that is unlikely to change anytime 
soon and thus missing the fast evolution of C++ language. 
</p>
</details>

<details>
<summary>Feature Coverage</summary>
<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>JVM Feature</th>
      <th>Module</th>
      <th>Status</th>
      <th>Issue Tracker</th>
      <th>Applicable C++ standard version</th>
      <th>Benchmarks</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>SH-1</td>
      <td>Shared</td>
      <td>Param parsing</td>
      <td>In Progress</td>
      <td><a href="https://github.com/NiinS/prakamya-j24/issues/3">#2</a></td>
      <td>C++20</td>
      <td>((benchmark link))</td>
      <td>SFINAE replaced with concepts</td>
    </tr>
    <tr>
      <td>(more features...)</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td>((benchmark link))</td>
      <td></td>
    </tr>
  </tbody>
</table>
</details>

<details>
<summary>Deprecated Feature Transformation</summary>
Features which were deprecated OR are no longer supported in the latest C++ standard.
<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Feature</th>
      <th>Status</th>
      <th>Issue Tracker</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>DF-1</td>
      <td>-Werror=volatile</td>
      <td>In Progress</td>
      <td><a href="https://github.com/NiinS/prakamya-j24/issues/2">#1</a></td>
      <td>Deprecated in C++17 and removed in C++20</td>
    </tr>
    <tr>
      <td>DF-2</td>
      <td>-Werror=deprecated-enum-enum-conversion</td>
      <td>In Progress</td>
      <td><a href="https://github.com/NiinS/prakamya-j24/issues/2">#1</a></td>
      <td></td>
    </tr>
    <tr>
      <td>(more...)</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
</details>

<details>
<summary>Pre-Built Prakamya Binaries</summary>
<table>
  <thead>
    <tr>
      <th>Release Date</th>
      <th>Version</th>
      <th>Download Link</th>
      <th>Milestones Achieved</th>
      <th>Minimum ToolChain Required</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TBD</td>
      <td>TBD</td>
      <td>TBD</td>
      <td><a href="https://github.com/NiinS/prakamya-j24/milestone/1">Milestone 1</a></td>
      <td>TBD</td>
      <td>TBD</td>
    </tr>
  </tbody>
</table>
</details>
</div>

<details>
<summary>Building Prakamya</summary>
Standard build instructions apply (needs a GCC compiler supporting >= C++26)

For build instructions please see the
- [doc/building.html](doc/building.html) (html version)
- [doc/building.md](doc/building.md) (markdown version)

OR

[online documentation](https://openjdk.org/groups/build/doc/building.html)

</details>

<hr/>
Contact: sin.nitins@gmail.com (nitin-s) for any enquiries or suggestions. Feel free to raise an enhancement request via the issue tracker.
