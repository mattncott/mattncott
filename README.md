[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Hi+I'm+Matt!)](https://git.io/typing-svg)

You should checkout my [Github Pages](https://mattncott.github.io/)

```c#
namespace MattNethercott
{
    public static class About : Me
    {
        public static IWorkPlace GetCurrentWorkPlace()
            => new WorkPlace
            {
                Company = "SS&C Blue Prism",
                Position = "Software Engineer"
            };

        public static IEnumerable<Technology> GetCurrentlyUsedTechnologies()
            => new List<Technology>
            {
                Technology.Net,
                Technology.VbNet,
                Technology.ReactJS,
                Technology.JavaScript,
                Technology.TypeScript,
                Technology.Docker,
                Technology.SQL,
                Technology.Azure
            };

        public static Technology GetWhatAmICurrentlyLearning()
            => Technology.Kubernetes;

        public static string GetMyGoal()
            => "To one day become a Software Architect";

    }
}
```

<!--
**mattncott/mattncott** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
