===== What's this? =====
This is a clone of Google Skia (website here) on 2011/6/27. The original project needs python to generate the project file to build it. I modify it a bit, removed many unrelated things (examples). And added VS2010 project file. You can then build Skia on Windows with a few clicks in VS2010.

===== Something worth mention =====
1. Moved SkTextBox.cpp from "Project views" to "Project core". I think we need SkTextBox most of the time. But other things in "Project views", we don't need them. So now we don't have to link with views.lib to use SkTextBox.
2. Removed SkFlate.cpp and its belonging project "zlib"