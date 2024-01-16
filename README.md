import streamlit as st

st.set_page_config(
    page_title="Shunxi Wu - UX Design and Product Management",
    page_icon="👩‍💻",
    layout="centered",
    initial_sidebar_state="auto",
)

col1, col2 = st.columns([0.3, 0.7])
with col1:
    st.markdown(
        """
    <style>
    .profile-img img {
        width: 100%;
        border-radius: 50%;
    }
    </style>

    <div class="profile-img">
        <img src="https://i.imgur.com/nAAKjBl.jpeg" alt="Profile Image">
    </div>
    """,
        unsafe_allow_html=True,
    )
with col2:
    st.markdown(
        """
    # Shunxi Wu
    shunxiwu@gmail.com • +1 (425)-624-4688 • 248 118th SE #28, Bellevue, WA 98005

    ## Objective
    Dedicated to pursuing a career in UX Design and Product Management, leveraging a strong foundation
    in pharmacy, proficient technical skills, and a proven track record of leadership.

    ## Education
    - **Master of Human Computer Interaction:** Global Innovation Exchange (GIX) Program
      Tsinghua University - University of Washington, Expected Graduation: April 2025
    - **Bachelor of Pharmacy:** Fudan University, Shanghai, China (2018 - 2022)
      Graduated with a degree in Pharmacy

    ## Professional Experience
    - **Intern, Shanghai Food Inspection Institute, Shanghai, China (July 2020 - September 2020)**
      - Administered food chemical component inspections, ensuring adherence to standards.
      - Analyzed data to identify discrepancies and contributed to improved inspection processes.

    ## Leadership in Projects
    - **PaiPai (2020) Party Planning Software Proposal**
      - Orchestrated the planning of a party management software.
      - Delegated tasks and coordinated cross-cultural teams for seamless execution.
      - Developed and executed strategies to find teams, venues, and specialized party personnel.

    - **Wander Flow (2023) AI System and Product**
      - Led the design and development of the ”Wander Flow” AI system.
      - Executed machine learning techniques on EEG and heart rate data to enhance study focus.

    - **ByeBye Acne (2023 - Present) Acne Diagnosis AI App Startup**
      - Co-founded a startup focused on AI-driven acne diagnosis.
      - Engineered AI models for medication recommendations and acne severity classification.
      - Promoted the app for personalized skincare routines.

    - **Knee Replacement Rehabilitation Motion Recognition System (Ongoing)**
      - Currently heading the development of an AI system to recognize post-surgery patient movements using IMU signals.
      - Streamlined and optimized the rehabilitation process with AI technology.

    ## Skills and Technologies
    - Proficient in Python, Arduino, writing AIGC prompt, Fusion360, and Inkscape.
    - Fluent in Chinese and English, with basic Spanish.
    - Strong background in project management, data analysis, and AI model development.

    ## Additional Information
    - Contributed expertise to support HIV/AIDS patients at Shanghai HCMC in 2020, offering counseling and educational support.
    - Avid collector of antique textiles, particularly from the Chinese Miao culture.
    """
    )

# Contact
st.markdown("# Contact")

# LinkedIn
col1, col2, col3 = st.columns(3)

# LinkedIn Logo
col1.markdown(
    """
    <style>
    .profile-img img {
        width: 100%;
        border-radius: 10%;
    </style>

    <div class="profile-img">
        <a href="https://www.linkedin.com/in/shunxi-wu-276022236/" target="_blank">
            <img src="https://i.imgur.com/OQUXwNp.jpeg" alt="LinkedIn">
        </a>
    </div>
    """,
    unsafe_allow_html=True,
)

# Facebook Logo
col2.markdown(
    """
    <style>
    .profile-img img {
        width: 100%;
        border-radius: 10%;
    </style>

    <div class="profile-img">
        <a href="https://www.facebook.com/profile.php?id=100002535667516" target="_blank">
            <img src="https://i.imgur.com/QQ89Rt3.jpeg" alt="Facebook">
        </a>
    </div>
    """,
    unsafe_allow_html=True,
)

# GitHub Logo
col3.markdown(
    """
    <style>
    .profile-img img {
        width: 100%;
        border-radius: 10%;
    </style>

    <div class="profile-img">
        <a href="https://github.com/ShunxiWu" target="_blank">
            <img src="https://i.imgur.com/J6LeoUb.png" alt="GitHub">
        </a>
    </div>
    """,
    unsafe_allow_html=True,
)

# Footer
ft = """
<style>
a:link , a:visited{
color: #BFBFBF;
background-color: transparent;
text-decoration: none;
}

a:hover,  a:active {
color: #0283C3;
background-color: transparent;
text-decoration: underline;
}

#page-container {
  position: relative;
  min-height: 10vh;
}

.footer {
position: relative;
left: 0;
top:230px;
bottom: 0;
width: 100%;
background-color: transparent;
color: #808080;
text-align: left;
}
</style>

<div id="page-container">

<div class="footer">
<p style='font-size: 0.875em;'>Made with <a style='display: inline; text-align: left;' href="https://streamlit.io/" target="_blank">Streamlit</a><br 'style= top:3px;'>
with <img src="https://em-content.zobj.net/source/skype/289/red-heart_2764-fe0f.png" alt="heart" height= "10"/><a style='display: inline; text-align: left;' href="https://github.com/sape94" target="_blank"> by sape94</a></p>
</div>

</div>
"""
st.write(ft, unsafe_allow_html=True)
