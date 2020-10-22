+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Research Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Research on Combining and Precoding Algorithms in Cell-Free Massive MIMO System"
  company = "Master Project"
  company_url = ""
  # location = "California"
  date_start = "2019-06-01"
  date_end = "2020-06-01"
  description = """
   Developing from the distributed Massive MIMO system, the Cell-Free Massive MIMO system gradually becomes one of the most promising structures for the next generation mobile communication system.
  
  * Analyzed the model of Cell-Free Massive MIMO system and simulated the downlink and uplink spectrual efficiency with different precoding and combining algortihms when considering fronthaul limitaion
  * Designed a precoding and combining scheme based on Convolutional Neural Network, which improves spectrual efficiency of the system while maintaining a relatively low computation complexity
  * Proposed a novel user-centric architecture to solve scability problem faced by Cell-Free Massive MIMO system, and optimized the AP selection schemes
  """
  
[[experience]]
  title = "Embedded Ad-hoc Communication Network with LoRa Protocol"
  company = ""
  company_url = ""
  # location = "California"
  date_start = "2018-06-01"
  date_end = "2019-03-01"
  description = """
   Designed communication network for decentralized circumstance using LoRa, which is a popular communication protocol widely used in IoT systems

  * Employed AODV as routing protocol and included CSMA in MAC protocol
  * Improved the robustness of Ad-hoc network with a feedback scheme
  * Able to set up center nodes if needed and communicate with the cloud server, which is a competent design for a variety of IoT scenarios
  """
  
  [[experience]]
  title = "Channel Estimation and Demodulation Schemes for MIMO System with Nonlinear PAs"
  company = "Undergraduate Project"
  company_url = ""
  # location = "California"
  date_start = "2017-09-01"
  date_end = "2018-06-01"
  description = """
   Power amplifier’s nonlinearity causes the distortion of the transmitting signal in wireless communication systems, including MIMO system
  
  * Employed the support vector regression (SVR) algorithm to fit the nonlinearity of the power amplifier in the MIMO system and compensate for the nonlinearity after the channel estimation
  * Designed an asymmetric demodulation method based on K-means algorithm in order to eliminate the effect of nonlinearity on demodulation, which turns out to outperform tradational demodulation methods
  * Conducted hardware experiments based on universal software radio peripheral(USRP) to verify the proposed algorithms
  """
  
  [[experience]]
  title = "A Remote Teaching System for Electric Piano"
  company = "Award-winning Work"
  company_url = ""
  # location = "California"
  date_start = "2017-05-01"
  date_end = "2017-09-01"
  description = """
   Designed and built a novel remote teaching system for electric piano based on FPGA and embedded system
  
  * Able to transmit real-time key-press information between users, and control any piano in the system to play automatically
  * Win the first prize (champion) of 2017 National Undergraduate IOT Design Contest
  """
  

+++
