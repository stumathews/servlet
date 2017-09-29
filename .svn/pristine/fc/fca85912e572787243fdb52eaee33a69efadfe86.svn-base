/** Skeleton code for implementing a servlet in a EEContainer */

import javax.servlet.http.HttpServletRequest;
import javax.servelt.http.HttpServletResponse;
import javax.servlet.http.HttpServlet;

public class MyServlet extends HttpServlet
{
    /** Note we dont need to implement a constructor - but we can */
    
    /**
       This is the first method that gets invoked on creation of the servlet, can be seen as a constructor, I guess
     */
    public void init()
    {
	
    }
    /**
       Process a GET request sent from the client, construct a response
     */
    public void doGet( HttpServletRequest req, HttpServletResponse resp)
    {
	/** Construct a respoonse; */
	resp.setContentTyoe("text/HTML"); // This could XML
	PrintWriter out resp.getWriter();


	out.println("<HTML>");
	out.println("<HEAD>");
	out.println("<TITLE> The title </TITLE>");
	out.println("</HEAD>");
	out.println("<BODY>");
	out.println("<P>This is the response the servlet constructed</P>");
	out.println("</BODY>");

    }

    /**
       Process a POST request from the client, construct a response
     */
    public void doPost(HttpServletRequest req, HttpServletResponse resp)
    {
	/** Typically you'd want to get the POST variables sent in the request */
	String userName = req.getParameter("USERNAME"); // This was the name in the input HTML tag
    }
}