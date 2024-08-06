<script>
    import Step from "./Step.svelte";

    let steps = [
        {
            git: "https://github.com/deadlykittensgs/guitarJS",
            href: "https://clinquant-toffee-6e2fb4.netlify.app/",
            name: "Guitar Problem Solver",
            icon: "fa-solid fa-guitar",
            description:
                "Guitarist tool to learn quickly",
        },
        {
            git: "https://github.com/deadlykittensgs/passwordGame",
            href: "https://passwordgamerm.netlify.app/",
            name: "Passwords Game",
            icon: "fa-solid fa-unlock-keyhole",
            description:
                "Passwords Game",
        },
        {
            git: "https://github.com/deadlykittensgs/allisasBBQ",
            href: "https://ryansbbqandbar.netlify.app/",
            name: "BBQ Restaurant",
            icon: "fa-solid fa-utensils",
            description:
                "Nasa API",
        },
        {
            git: "https://github.com/deadlykittensgs/Nasa",
            href: "https://dailynasa.netlify.app/",
            name: "NASA API",
            icon: "fa-solid fa-diagram-project",
            description:
                "Nasa API",
        },
        {
            git: "https://github.com/deadlykittensgs/react-weather-app",
            href: "https://calm-sorbet-5949f6.netlify.app/",
            name: "Daily Weather App",
            icon: "fa-solid fa-cloud-sun-rain",
            description:
                "react and tailwind weather app",
        },
        {
            git: "https://github.com/deadlykittensgs/swoley",
            href: "https://workoutpage.netlify.app/",
            name: "Workout Helper",
            icon: "fa-solid fa-dumbbell",
            description:
                "react and tailwind weather app",
        },
        
        
    ];

    let benefits = [
        {
            metric: "10x",
            name: "A self taught developer",
            description:
                "I taught myself to code using free online resources and absolutely fell in love with the creativity and problem solving that is involved in developing and engineering innovative new online experiences. Starting of with JavaScript, HTML & CSS and evolving my knowledge base to include JavaScript frameworks, backend programming, design, cloud services and much much more.",
        },
        {
            name: "A product design & UX fanatic",
            description:
                "Carefully crafting and designing amazing user experiences allows me to express and experiment with every morsel of creativity I have. I love the challenge of learning new design concepts and enabling users with amazing online experiences.",
        },
        {
            name: "An excellent communicator",
            description:
                "Communication is key and it's a paramount value of mine. I believe in transparency and constructive communication above all else. This helps me develop deep relationships and ensures my effectiveness and productivity in any work space with any team.",
        },
    ];
</script>
<main class="flex flex-col flex 1 p-4 ">
    <section
    id="introPage"
    class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14 "
>
    <div
        class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
    >
        <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl ">
            Hi! I'm <span class="poppins text-violet-400">Ryan</span> McMahon
            <br />Full Stack
            <span class="poppins text-violet-400">Developer</span>
        </h2>
        <p class="text-base sm:text-lg md:text-xl ">
            My <span class="text-violet-400"> favorite tech</span> includes JavaScript
            (React.JS), TailwindCSS, Node.JS + Express.JS!
           
        </p>
        <a
            class="blueShadow flex item-center mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950" href="https://github.com/deadlykittensgs" target="_blank"
        >
            <div
                class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
            />
            <h4 class="relative z-9" >Get in touch &rarr;</h4>
        </a>
    </div>
    <div class="relative shadow-2xl grid place-items-center">
        <img src={"/images/ryan m-fotor-bg-remover-20240511153120.png"} alt="Profile Image" 
        class="object-cover z-[2] max-h-[70vh]"/>
    </div>
    
</section>



<section class="py-20 lg:py-32 flex flex-col gap-24" id="projects" >
    <div class="flex flex-col gap-2 text-center">
        <h6 class="text-large sm:text-xl md:text-2xl">
            A few of my creative endeavors.
        </h6>
        <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
            Curious to <span class="poppins text-violet-400">see</span> my work?
        </h3>
    </div>
<div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
    <Step step={steps[0]}>
        <p>
            Guitar Problem Solver is a <strong class="text-violet-400"> Javascript </strong> application features a <strong class="text-violet-400">dynamically generated fretboard </strong>,
            leveraging music theory to display corresponding notes on the neck based on the chords being played.
            It offers an interactive and <strong class="text-violet-400">educational tool</strong> for guitarists to enhance their understanding and execution of
            chord structures.
            
        </p>
    </Step>

    <Step step={steps[1]}>
        <p>
          Passwords Game is a <strong class="text-violet-400">React.JS</strong> application connected to a <strong class="text-violet-400">interactive Firebase Firestore database</strong> 
          to allow users to add words from any device at any time and then play the game on a single phone. The game includes a timer to lock buttons after the time limit has expired and a interactive score board.
        </p>
    </Step>

    <Step step={steps[2]}>
        <p>
             BBQ Restaurant app, crafted with <strong class="text-violet-400">React.JS and Tailwind CSS</strong>, is a sleek, five-page showcase for small businesses.
              It boosts credibility by displaying hours, location <strong class="text-violet-400">(with an integrated map)</strong>, product offerings, prices, descriptions, and unique images. The app features a catering 
              request page and a job application page, both <strong class="text-violet-400">seamlessly connected to EmailJS</strong>, ensuring direct communication with the business owner.
        </p>
    </Step>
    <Step step={steps[3]}>
        <p>
            Nasa API is a  <strong class="text-violet-400"> React</strong> application that provides a 
            framework for the data extracted form the <strong class="text-violet-400"> Nasa API</strong> to be displayed clearly
            on any screen size and to changed daily.  
       
    </p>
        
       
    </Step>
    <Step step={steps[4]}>
    <p>
        The Daily Weather app was created to pull the daily weather information 
        from an <strong class="text-violet-400">API</strong> and displaying it dynamical using <strong class="text-violet-400">React.js</strong> and <strong class="text-violet-400">Tailwinds</strong> as well as featuring a  <strong class="text-violet-400">location lookup feature </strong>
        which is triggered on load
    </p>
    </Step>
     <Step step={steps[5]}>
        <p>
            #StayHard is a workout app using exercise routine data from one of my favorite content creators <strong
            class="text-violet-400">James</strong>. The app was built primarily using <strong
                class="text-violet-400"> React and TailwindCSS and is hosted on Netlify.</strong
            > It is intended to give you an en energizing workout routine targeted specifically at the muscle groups you select.
        </p>
    </Step>
</div>
</section >


<section
id="about"
class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
>
<div
    class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
>
    <h6 class="text-large sm:text-xl md:text-2xl">
        Want to know more?
    </h6>
    <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        A bit <span class="poppins text-violet-400">about</span> me.
    </h3>

</div>
<p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
    I am . . .
</p>

<div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
    {#each benefits as benefit, index}
        <div class="flex gap-6 sm:gap-8">
            <p
                class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
            >
                0{index + 1}
            </p>
            <div class="flex flex-col gap-6 sm:gap-8">
                <h3 class="text-2xl sm:text-3xl md:text-5xl">
                    {benefit.name}
                </h3>
                <p>{benefit.description}</p>
            </div>
        </div>
    {/each}
</div>
<h5 class={" text-2xl sm:text-3xl font-semibold text-center poppins "}>
    The <span class="text-violet-400">Complete</span> Package
</h5>
<div
    class="flex flex-col overflow-x-scroll gap-10 max-w-[800px] mx-auto w-full"
>
    <table class="bg-white text-slate-700 rounded text-center">
        <thead class={"border-b border-solid border-slate-200  "}>
            <tr class="">
                <th />
                <th class="whitespace-nowrap p-2 px-4">Candidate #1</th>
                <th class="whitespace-nowrap p-2 px-4">Candidate #2</th>
                <th class="whitespace-nowrap p-2 px-4">Candidate #3</th>
                <th
                    class="bg-violet-700 text-white whitespace-nowrap p-4 px-8"
                    >Me</th
                >
            </tr>
        </thead>
        <tbody>
            <tr class="border-b border-solid border-slate-200">
                <td
                    class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                    >Dedication</td
                >
                <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                <td><i class="fa-solid fa-check text-slate-500" /></td>
                <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                <td><i class="fa-solid fa-check text-green-500" /></td>
            </tr>
            <tr class="border-b border-solid border-slate-200">
                <td
                    class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                    >Critical Thought</td
                >
                <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                <td><i class="fa-solid fa-check text-slate-500" /></td>
                <td><i class="fa-solid fa-check text-slate-500" /></td>
                <td><i class="fa-solid fa-check text-green-500" /></td>
            </tr>
            <tr>
                <td
                    class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                    >Interpersonal Skills</td
                >
                <td><i class="fa-solid fa-check text-slate-500" /></td>
                <td><i class="fa-solid fa-check text-slate-500" /></td>
                <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                <td><i class="fa-solid fa-check text-green-500" /></td>
            </tr>
            <tr class="border-t border-solid border-slate-200">
                <td
                    class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                    >Programming Ability</td
                >
                <td><i class="fa-solid fa-check text-slate-500" /></td>
                <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                <td><i class="fa-solid fa-check text-slate-500" /></td>
                <td><i class="fa-solid fa-check text-green-500" /></td>
            </tr>
        </tbody>
    </table>
</div>
<div class="mx-auto -mt-12 italic sm:hidden opacity-50">
    <p>Scroll to see more &rarr;</p>
</div>
<p class="mx-auto">So why not invest?</p>
</section>

</main>
