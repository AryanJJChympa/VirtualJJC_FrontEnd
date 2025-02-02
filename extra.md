<div className="lg:hidden md-flex flex-col justify-end">
                    <button onClick={toggleNavbar}>
                        {mobileDrawerOpen?<X/> : <Menu/>}
                    </button>
                </div>


                const [mobileDrawerOpen, setMobileDrawerOpen] = useState(false);

    const toggleNavbar=()=>{
        setMobileDrawerOpen(!mobileDrawerOpen);
    }