package customplugin.wizards;

import org.eclipse.jface.viewers.IStructuredSelection;
import org.eclipse.jface.wizard.Wizard;
import org.eclipse.ui.INewWizard;
import org.eclipse.ui.IWorkbench;
import org.eclipse.ui.dialogs.WizardNewProjectCreationPage;

public class BuilderNewWizard extends Wizard implements INewWizard {
    private WizardNewProjectCreationPage _pageOne;

    public BuilderNewWizard() {
        // Set the title of your new wizard
        setWindowTitle("IoT Suite");
    }

    @Override
    public void init(IWorkbench workbench, IStructuredSelection selection) {
        // Initialize your wizard
    }

    @Override
    public boolean performFinish() {
        // Perform any necessary actions when the user clicks Finish
        // For file creation, you'll need to add logic here
        // Example: Create a new file with predefined content
        // You can use IFile or File API to create the file
        // ...
        return true;
    }

    @Override
    public void addPages() {
        super.addPages();
        // Create a page with title and other attributes
        _pageOne = new WizardNewProjectCreationPage("From Scratch Project Wizard");
        _pageOne.setTitle("IoT Suite Configuration");
        _pageOne.setDescription("Create IoTSuite Configuration");
        addPage(_pageOne);
    }
}
