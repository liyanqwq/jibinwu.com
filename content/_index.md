---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor
          company: The Hong Kong Polytechnic University
          company_url: 'https://www.polyu.edu.hk'
          location: Hong Kong
          date_start: '2022-09-19'
          date_end: ''
        - title: Research Scientist
          company: Sea AI Lab (SAIL)
          company_url: 'https://sail.sea.com/'
          location: Singapore
          date_start: '2021-01-01'
          date_end: '2022-09-01'
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: team
    id: team
    content:
      title: Research Team
      members:
        - title: Postdoc Fellows
          members:
            - name: Xun ZHOU
              image: media/albums/team/xun_zhou.webp
              interests:
                - Evolutionary algorithm
                - Neural architecture search
            - name: Hao CHENG
              image: media/albums/team/hao_cheng.webp
              interests:
                - Data-driven Materials Design Machine Learning
                - Accelerated Atomistic Simulations
            - name: Yuxiao HUANG
              image: media/albums/team/yuxiao_huang.webp
              interests:
                - Evolutionary Transfer Optimization
                - Combinatorial Optimization
                - Parallel Computing
            - name: Tong YANG
              image: media/albums/team/tong_yang.webp
              interests:
                - High-throughput Calculations
                - Material discovery
            - name: Xingyu WU
              image: media/albums/team/xingyu_wu.webp
              interests:
                - Large Foundation Models
                - Causality-based Machine Learning
            - name: Shenghao WU
              image: media/albums/team/shenghao_wu.webp
              interests:
                - Evolutionary Transfer Optimization
                - Transfer Learning
                - Data-driven Optimization
        - title: PhD Students
          members:
            - name: Beichen HUANG
              image: media/albums/team/huang_beichen.webp
              interests:
                - High-performance Evolutionary Computation
                - Neuro-evolution
            - name: Xinmeng XU
              image: media/albums/team/xu_xinmeng.webp
              interests:
                - Speech Enhancement
                - Acoustic Echo Cancellation
                - Robot Audition
            - name: Yinsong YAN 
              image: media/albums/team/yan_yinsong.webp
              interests:
                - Brain-inspired Computing
                - Spiking Neural Networks
            - name: Yu ZHOU
              image: media/albums/team/zhou_yu.webp
              interests:
                - Federated Learning
                - Evolutionary Computation
                - Deep Reinforcement Learning
            - name: Haokai HONG
              image: media/albums/team/hong_haokai.webp
              interests:
                - Multi-objective Optimization
                - Large-scale Optimization
            - name: Ziyuan YE
              image: media/albums/team/ye_ziyuan.webp
              interests:
                - NeuroAI
                - AGI
                - Deep Learning
            - name: Yajie ZHANG 
              image: media/albums/team/zhang_yajie.webp
              interests:
                - Multimodal Biomedical AI
                - Causal Inference
                - Domain Adaptation
            - name: Xiang HAO
              image: media/albums/team/hao_xiang.webp
              interests:
                - Audio/Speech Signal Processing
            - name: Cheng CHEN
              image: media/albums/team/chen_cheng.webp
              interests:
                - Game theory  
                - Mechanism design
                - Fair allocation
            - name: Xinyi CHEN
              image: media/albums/team/chen_xinyi.webp
              interests:
                - Neuromorphic Computing
                - Spiking Neural Networks
            - name: Wu LIN
              image: media/albums/team/lin_wu.webp
              interests:
                - Evolutionary Computation
                - Evolutionary Transfer Optimization
            - name: Chenxiang MA
              image: media/albums/team/ma_chenxiang.webp
              interests:
                - Spiking Neural Network
                - Local Learning
            - name: Zhenzhong WANG
              image: media/albums/team/wang_zhenzhong.webp
              interests:
                - Machine Learning
                - Evolutionary Computation
            - name: Yao HU
              image: media/albums/team/hu_yao.webp
              interests:
                - Domain Adaptation
                - Federated Learning
                - Medical AI
            - name: Xiaoming XUE
              image: media/albums/team/xue_xiaoming.webp
              interests:
                - Evolutionary Transfer Optimization
                - Engineering Design Optimization
            - name: Rui LIU
              image: media/albums/team/liu_rui.webp
              interests:
                - Medical Diagnosis 
                - Deep Learning
            - name: Yinglan FENG
              image: media/albums/team/feng_yinglan.webp
              interests:
                - Multiform Optimization
                - Evolutionary Transfer Optimization
        - title: Research Assistant
          members:
            - name: Kaixuan YANG
              image: media/albums/team/yang_kaixuan.webp
              interests:
                - Audio Signal Processing
                - Speech Enhancement
            - name: Mengqi XU
              image: media/albums/team/xu_mengqi.webp
              interests:
                - Machine Learning
        - title: Alumni
          members:
            - name: Songbai LIU
              link: https://csse.szu.edu.cn/pages/user/index?id=1267
              time: 2019 - 2022
              type: Ph.D. Student
              text: Assistant Professor, Shenzhen University
            - name: Zhian HUANG
              link: https://huangza.wixsite.com/mysite
              time: 2018 - 2021
              type: Ph.D. Student
              text: Research Fellow, City University of Hong Kong (Dongguan)
    design:
      columns: '1'
  - block: accomplishments
    content:
      title: 'Editorial and<br />Community<br />Service'
      items:
        - organization: 'IEEE Transactions on Neural Networks and Learning Systems (IF: 10.4)'
          title: Associate Editor
        - organization: 'IEEE Transactions on Cognitive and Developmental Systems (IF: 5.0)'
          title: Associate Editor
        - organization: Natural Language Processing Journal
          title: Editor
        - organization: 'IEEE (Hong Kong) Computational Intelligence Chapter'
          title: 'Executive Committee Member'
        - organization: 'ICASSP-2022 Special Session on &#34;Towards neuromorphic machine intelligence: spike-based representation, learning, and signal processing&#34;'
          title: Organizer
    design:
      columns: '2'
  - block: collection
    id: publication
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: accomplishments
    content:
      title: 'Award & Grant'
      items:
        - date_start: '2023-01-01'
          organization: Intel Neuromorphic Deep Noise Suppression Challenge
          title: Track 1 (Algorithmic) Winner with Cash Prize of USD 15,000
        - date_start: '2019-01-01'
          organization: International Collegiate Competition for Brain-inspired Computing
          title: Second Prize of Final Contest with Cash Prize of RMB 60,000
          description: Tsinghua University, China (Team Leader)
        - date_start: '2019-01-01'
          organization: Zhejiang Lab
          title: Zhejiang Lab’s International Talent Fund for Young Professionals
        - date_start: '2019-01-01'
          title: Travel Grant to 2nd Annual EPFL Engineering PhD Summit
        - date_start: '2019-01-01'
          date_end: '2020-01-01'
          organization: National University of Singapore
          title: President’s Graduate Fellowship
        - date_start: '2018-01-01'
          organization: International Collegiate Competition for Brain-inspired Computing
          title: First Prize of Final Contest with Cash Prize of RMB 100,000
          description: Tsinghua University, China (Team Leader)
        - date_start: '2018-01-01'
          organization: 2018 Electrical and Computer Engineering Graduate Student Symposium
          title: Best Presentation Award
          description: National University of Singapore
        - date_start: '2016-01-01'
          date_end: '2019-01-01'
          organization: National University of Singapore
          title: NUS Research Scholarship
    design:
      columns: '2'
  - block: accomplishments
    content:
      title: 'Invited Talks'
      date_format: Jan 2006
      items:
        - date_start: '2023-08-01'
          title: 2nd International Conference on Smart Technologies For Smart Nation
          organization: Singapore
        - date_start: '2023-07-01'
          title: CAAI International Conference on Artificial Intelligence
          organization: Fuzhou, China
        - date_start: '2023-04-01'
          title: IEEE CIS Shenzhen Chapter Spring Workshop
          organization: Shenzhen, China
        - date_start: '2022-11-01'
          title: ACCESS-CEDA Seminar
          organization: Online
        - date_start: '2020-11-01'
          title: Northwest Normal University Research Seminar
          organization: Online
        - date_start: '2020-07-01'
          title: INTEL Neuromorphic Research Community Forum
          organization: Online
        - date_start: '2020-06-01'
          title: Japan National Institute of Informatics
          organization: Online
        - date_start: '2019-12-01'
          title: Tsinghua University Student Overseas Practicing Program
          organization: Singapore
        - date_start: '2019-10-01'
          title: INTEL Neuromorphic Research Community Fall Workshop
          organization: Graz, Austria
        - date_start: '2019-10-01'
          title: 2nd Annual EPFL Engineering PhD Summit
          organization: EPFL, Lausanne, Switzerland
    design:
      columns: '2'
---
