const greeting = {
  username: "Sudip Adhikari",
  title: "Hi all, I'm Sudip 👋",
  subTitle: "A passionate Forestry Student, Wildlife Researcher & GIS Enthusiast from Nepal 🌿🦉",
  resumeLink: "https://example.com/sudip-resume.pdf", // replace with your real link later
};

const socialMediaLinks = {
  github: "https://github.com/khanalbishal96",
  linkedin: "https://linkedin.com/in/sudipadhikari", // replace or leave as is
  gmail: "sudip.forestry@gmail.com",
};

const skillsSection = {
  title: "What I do",
  subTitle: "I use maps, research, and awareness to conserve nature",
  skills: [
    "📍 Conduct wildlife surveys and habitat assessments",
    "📊 Use GIS and remote sensing for conservation mapping",
    "📢 Educate students on climate change and biodiversity",
  ],
  softwareSkills: [
    { skillName: "ArcGIS", fontAwesomeClassname: "logos:arcgis" },
    { skillName: "QGIS", fontAwesomeClassname: "logos:qgis" },
    { skillName: "R Programming", fontAwesomeClassname: "logos:r" },
    { skillName: "Google Earth Engine", fontAwesomeClassname: "logos:google-earth-engine" },
    { skillName: "Microsoft Excel", fontAwesomeClassname: "vscode-icons:file-type-excel" },
  ],
};

const educationInfo = {
  schools: [
    {
      schoolName: "Institute of Forestry, Hetauda",
      subHeader: "B.Sc. Forestry (Final Year)",
      duration: "2021 - 2025",
      desc: "Focused on wildlife research, habitat mapping, and ecological data analysis.",
    },
  ],
};

const projects = {
  data: [
    {
      id: "1",
      name: "Cheer Pheasant Conservation",
      description:
        "Conducted field surveys and awareness programs in Arghakhanchi District. Observed 11 individuals across 13 call count stations.",
      url: "#",
    },
    {
      id: "2",
      name: "Climate Change School Campaign",
      description:
        "Designed and ran awareness workshops on climate change and eco-club formation in 20+ rural schools.",
      url: "#",
    },
    {
      id: "3",
      name: "Habitat Suitability Mapping",
      description:
        "Used MaxEnt and QGIS to model habitat of Elongated Tortoise in Arghakhanchi District using environmental variables.",
      url: "#",
    },
  ],
};

const contactInfo = {
  title: "Contact Me ☎️",
  subtitle: "Want to talk about research, maps, or birds? Let's connect!",
  number: "+977-98XXXXXXXX",
  email_address: "sudip.forestry@gmail.com",
};

export {
  greeting,
  socialMediaLinks,
  skillsSection,
  educationInfo,
  projects,
  contactInfo,
};
