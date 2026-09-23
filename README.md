{
  "name": "Bhavishya Dahiya",
  "github": "Bhavishyadahiya",
  "profile": {
    "role": "Student / Developer",
    "primary_interests": [
      "Linux",
      "Docker",
      "Networking",
      "Automation",
      "Self-hosting",
      "Developer tooling",
      "IP and proxy tooling",
      "Bandwidth-node infrastructure"
    ],
    "development_style": [
      "Practical",
      "Automation-first",
      "CLI-focused",
      "Infrastructure-oriented",
      "Prefers lightweight solutions"
    ]
  },

  "technical_stack": {
    "languages": [
      "Bash",
      "Shell scripting",
      "HTML"
    ],
    "platforms": [
      "Linux",
      "Docker",
      "Arch Linux",
      "Debian"
    ],
    "tools": [
      "Docker",
      "tun2proxy",
      "curl",
      "Git",
      "GitHub",
      "systemd"
    ],
    "networking": [
      "HTTP",
      "HTTPS",
      "SOCKS4",
      "SOCKS5",
      "Proxy routing",
      "DNS",
      "IP intelligence",
      "Network namespaces"
    ],
    "apis": [
      "ip-api.com",
      "RapidAPI",
      "Ping0"
    ]
  },

  "projects": [
    {
      "name": "EAincome",
      "repo": "Bhavishyadahiya/EAincome",
      "type": "Docker / automation",
      "description": "EarnApp-focused Docker node deployment and management.",
      "technologies": [
        "Bash",
        "Docker",
        "tun2proxy",
        "Linux",
        "Networking"
      ],
      "features": [
        "Multi-node deployment",
        "Per-proxy node routing",
        "Proxy validation",
        "DNS routing",
        "Docker image building",
        "Node persistence",
        "Container management",
        "TLS/certificate handling"
      ]
    },

    {
      "name": "IP-lookup",
      "repo": "Bhavishyadahiya/IP-lookup",
      "type": "CLI networking tool",
      "description": "Terminal-based proxy/IP intelligence checker.",
      "technologies": [
        "Bash",
        "curl",
        "ip-api.com",
        "RapidAPI"
      ],
      "features": [
        "IPv4 extraction",
        "Proxy format parsing",
        "Duplicate removal",
        "IP geolocation",
        "ISP lookup",
        "ASN lookup",
        "Risk scoring",
        "Datacenter detection",
        "Bogon detection",
        "Crawler detection",
        "Terminal UI"
      ]
    },

    {
      "name": "earnapp-docker",
      "repo": "Bhavishyadahiya/earnapp-docker",
      "type": "Docker image",
      "description": "Unofficial Dockerized EarnApp deployment.",
      "technologies": [
        "Docker",
        "Arch Linux",
        "Bash"
      ],
      "features": [
        "Containerized EarnApp",
        "Persistent /etc/earnapp configuration",
        "Automatic installation",
        "Node registration"
      ]
    },

    {
      "name": "register",
      "repo": "Bhavishyadahiya/register",
      "type": "Domain registration project",
      "description": "Repository related to is-a.dev domain registration.",
      "technologies": [
        "Git",
        "GitHub",
        "JSON"
      ]
    },

    {
      "name": "mainwebshit",
      "repo": "Bhavishyadahiya/mainwebshit",
      "type": "Web",
      "description": "Minimal personal web project."
    }
  ],

  "engineering_preferences": {
    "preferred_interface": "CLI",
    "preferred_automation": "Bash scripts and Docker",
    "preferred_deployment": "Containers",
    "preferred_operating_system": "Linux",
    "preferred_networking": "Explicit proxy and DNS control",
    "preferred_configuration": "Simple editable config files",
    "logging": "Useful but controlled",
    "resource_usage": "Prefer lightweight implementations"
  },

  "common_tasks": [
    "Automating Docker deployments",
    "Managing multiple networked containers",
    "Proxy validation and routing",
    "IP intelligence and classification",
    "Linux troubleshooting",
    "Network debugging",
    "Self-hosted services",
    "CLI tooling",
    "Infrastructure experimentation"
  ],

  "coding_guidelines": {
    "shell": [
      "Prefer Bash for automation",
      "Validate configuration before starting containers",
      "Fail clearly on invalid input",
      "Avoid unnecessary dependencies",
      "Use configurable variables",
      "Keep secrets out of source code"
    ],
    "docker": [
      "Prefer reproducible builds",
      "Pin important images where practical",
      "Persist node/application state",
      "Keep containers independently manageable"
    ],
    "networking": [
      "Validate proxy syntax",
      "Make DNS behavior explicit",
      "Avoid accidental host DNS leakage",
      "Keep one logical network identity per node"
    ]
  },

  "interaction_preferences": {
    "answers": "Practical and direct",
    "code": "Complete working files when requested",
    "explanations": "Focus on commands and implementation",
    "avoid": [
      "Unnecessary abstractions",
      "Overly complicated solutions",
      "Heavy software when a lightweight alternative exists"
    ]
  }
}
