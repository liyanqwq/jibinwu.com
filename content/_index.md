---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

paper_highlight: 'J. Wu'

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
  - block: accomplishments
    content:
      title: 'Editorial Service'
      items:
        - organization: 'IEEE Transactions on Neural Networks and Learning Systems (IF: 10.4)'
          title: Associate Editor
        - organization: 'IEEE Transactions on Cognitive and Developmental Systems (IF: 5.0)'
          title: Associate Editor
        - organization: Natural Language Processing Journal
          title: Editor
    design:
      columns: '2'
  - block: accomplishments
    content:
      title: 'Professional Service'
      items:
        - organization: 'IEEE (Hong Kong) Computational Intelligence Chapter'
          title: 'Executive Committee Member'
        - organization: 'ICASSP-2022 Special Session on &#34;Towards neuromorphic machine intelligence: spike-based representation, learning, and signal processing&#34;'
          title: Organizer
    design:
      columns: '2'
  - block: team
    id: team
    content:
      title: Research Team
      members:
        - title: Postdoc Fellows
          members:
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
            # - name: Xinmeng XU
            #   image: media/albums/team/xu_xinmeng.webp
            #   interests:
            #     - Speech Enhancement
            #     - Acoustic Echo Cancellation
            #     - Robot Audition
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
            - name: Xinyi CHEN
              image: media/albums/team/xinyi_chen.jpg
              interests:
                - Neuromorphic Computing
                - Spiking Neural Networks
            - name: Chenxiang MA
              image: media/albums/team/ma_chenxiang.webp
              interests:
                - Spiking Neural Network
                - Local Learning
            - name: Zeyang SONG
              image: media/albums/team/zeyang_song.jpg
              interests:
                - Speech Processing
                - Spiking Neural Network
            - name: Qu YANG
              image: media/albums/team/qu_yang.jpg
              interests:
                - Spiking Neural Network
                - Neural Coding
                - Neuromorphic Computing
        - title: Research Assistant
          members:
            # - name: Kaixuan YANG
            #   image: media/albums/team/yang_kaixuan.webp
            #   interests:
            #     - Audio Signal Processing
            #     - Speech Enhancement
            - name: Mengqi XU
              image: media/albums/team/xu_mengqi.webp
              interests:
                - Machine Learning
        # - title: Alumni
        #   members:
        #     - name: Songbai LIU
        #       link: https://csse.szu.edu.cn/pages/user/index?id=1267
        #       time: 2019 - 2022
        #       type: Ph.D. Student
        #       text: Assistant Professor, Shenzhen University
        #     - name: Zhian HUANG
        #       link: https://huangza.wixsite.com/mysite
        #       time: 2018 - 2021
        #       type: Ph.D. Student
        #       text: Research Fellow, City University of Hong Kong (Dongguan)
    design:
      columns: '1'
  # - block: markdown
  #   content:
  #     title: Team Photos
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="team_photos" order="desc" >}}
  #   design:
  #     columns: '1'
  - block: accomplishments
    content:
      title: 'Award'
      items:
        - date_start: '2023-01-01'
          organization: Intel Neuromorphic Deep Noise Suppression Challenge
          title: Track 1 (Algorithmic) Winner with Cash Prize of USD 15,000
        - date_start: '2019-01-01'
          organization: International Collegiate Competition for Brain-inspired Computing
          title: Second Prize of Final Contest with Cash Prize of RMB 60,000
          description: Tsinghua University, China (Team Leader)
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
  - block: publication
    id: featured
    content:
      title: Featured Research
      content:
        - title: Spiking Neural Network Learning Algorithms
          content:
            - cite: 'Q. Yang, J. Wu*, M. Zhang, Y. Chua, X. Wang, H. Li, "Training Spiking Neural Networks with Local Tandem Learning", in _Advances in Neural Information Processing Systems_ (2022): 14516-14528.'
              url: https://proceedings.neurips.cc/paper_files/paper/2022/hash/523caec7832a47fb19b8471dbfeec471-Abstract-Conference.html
            - cite: 'J. Wu, C. Xu, X. Han, D. Zhou, M. Zhang, H. Li, and K. C. Tan, "Progressive Tandem Learning for Pattern Recognition with Deep Spiking Neural Networks. ", in _IEEE Transactions on Pattern Analysis and Machine Intelligence_, 2021.'
              url: https://ieeexplore.ieee.org/abstract/document/9543525/
            - cite: 'J. Wu, Y. Chua, M. Zhang, G. Li, H. Li, and K. C. Tan, "A Tandem Learning Rule for Effective Training and Rapid Inference of Deep Spiking Neural Networks.", in _IEEE Transactions on Neural Networks and Learning Systems_, 2021.'
              url: https://ieeexplore.ieee.org/abstract/document/9492305/
            
        - title: Neural Coding
          content:
            - cite: 'X. Chen, Q. Yang, J. Wu*, H. Li, and K. C. Tan, "A Hybrid Neural Coding Approach for Pattern Recognition with Spiking Neural Networks", in _IEEE Transactions on Pattern Analysis and Machine Intelligence_, doi: 10.1109/TPAMI.2023.3339211.'
              url: https://arxiv.org/abs/2305.16594
            - cite: 'Z. Pan, M. Zhang, J. Wu*, H. Li, "Multi-Tone Phase Coding of Interaural Time Difference for Sound Source Localization with Spiking Neural Networks", in _IEEE Transactions on Audio, Speech and Language Processing_, 2021.'
              url: https://ieeexplore.ieee.org/abstract/document/9502013/
            - cite: 'Z. Pan, Y. Chua, J. Wu, M. Zhang, H. Li, and E. Ambikairajah, "An Efficient and Perceptually Motivated Auditory Neural Encoding and Decoding Algorithm for Spiking Neural Networks.", in _Frontiers in Neuroscience_, vol. 13, pp. 1420, 2020.'
              url: https://www.frontiersin.org/articles/10.3389/fnins.2019.01420/full
        - title: Brain-inspired Neural Architecture Design
          content:
            - cite: 'S. Zhang, Q. Yang, C. Ma, J. Wu*, H. Li, and K. C. Tan. "TC-LIF: A Two-Compartment Spiking Neuron Model for Long-term Sequential Modelling.", in _AAAI-24_, Vancouver, Canada. (Accepted)'
              url: https://arxiv.org/abs/2308.13250
            - cite: 'Z. Pan, M. Zhang, J. Wu*, H. Li, "Multi-Tone Phase Coding of Interaural Time Difference for Sound Source Localization with Spiking Neural Networks", in _IEEE Transactions on Audio, Speech and Language Processing_, 2021. '
              url: https://ieeexplore.ieee.org/abstract/document/9502013/
            - cite: 'J. Wu, Z. Pan, M. Zhang, R. K. Das, Y. Chua, and H. Li, "Robust Sound Recognition: A Neuromorphic Approach.", in _INTERSPEECH_, Graz, Austria, 2019.'
              url: https://www.isca-speech.org/archive/interspeech_2019/wu19h_interspeech.html
        - title: Computational Audition & Speech Processing
          content:
            - cite: 'J. Wu, Q. Liu, M. Zhang, Z. Pan, H. Li, and K. C. Tan, "HuRAI: A Brain-Inspired Computational Model for Human-Robot Auditory Interface.", in _Neurocomputing_, 2021.'
              url: https://www.sciencedirect.com/science/article/pii/S0925231221013266
            - cite: 'J. Wu, E. Yılmaz, M. Zhang, H. Li, and K. C. Tan, "Deep Spiking Neural Networks for Large Vocabulary Automatic Speech Recognition.", in _Frontiers in Neuroscience_, vol. 14, pp. 199, 2020.'
              url: https://www.frontiersin.org/articles/10.3389/fnins.2020.00199/full
            - cite: 'J. Wu, Y. Chua, M. Zhang, H. Li, and K. C. Tan, "A Spiking Neural Network Framework for Robust Sound Classification.", in _Frontiers in Neuroscience_, vol. 12, pp. 836, 2018. 154'
              url: https://www.frontiersin.org/articles/10.3389/fnins.2018.00836/full
            - cite: 'C. Xu, W. Rao, J. Wu, H. Li, "Target Speaker Verification with Selective Auditory Attention for Single and Multi-talker Speech ", in _IEEE Transactions on Audio, Speech and Language Processing_, 2021.'
              url: https://ieeexplore.ieee.org/abstract/document/9502020/
    design:
      columns: '2'
      view: citation
  # - block: accomplishments
  #   content:
  #     title: 'Invited Talks'
  #     date_format: Jan 2006
  #     items:
  #       - date_start: '2023-08-01'
  #         title: 2nd International Conference on Smart Technologies For Smart Nation
  #         organization: Singapore
  #       - date_start: '2023-07-01'
  #         title: CAAI International Conference on Artificial Intelligence
  #         organization: Fuzhou, China
  #       - date_start: '2023-04-01'
  #         title: IEEE CIS Shenzhen Chapter Spring Workshop
  #         organization: Shenzhen, China
  #       - date_start: '2022-11-01'
  #         title: ACCESS-CEDA Seminar
  #         organization: Online
  #       - date_start: '2020-11-01'
  #         title: Northwest Normal University Research Seminar
  #         organization: Online
  #       - date_start: '2020-07-01'
  #         title: INTEL Neuromorphic Research Community Forum
  #         organization: Online
  #       - date_start: '2020-06-01'
  #         title: Japan National Institute of Informatics
  #         organization: Online
  #       - date_start: '2019-12-01'
  #         title: Tsinghua University Student Overseas Practicing Program
  #         organization: Singapore
  #       - date_start: '2019-10-01'
  #         title: INTEL Neuromorphic Research Community Fall Workshop
  #         organization: Graz, Austria
  #       - date_start: '2019-10-01'
  #         title: 2nd Annual EPFL Engineering PhD Summit
  #         organization: EPFL, Lausanne, Switzerland
  #   design:
  #     columns: '2'
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
  # - block: collection
  #   id: news
  #   content:
  #     title: News
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - news
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
---
