# MixerAPI Bake

[![Latest Version on Packagist](https://img.shields.io/packagist/v/mixerapi/bake.svg?style=flat-square)](https://packagist.org/packages/mixerapi/bake)
[![Build Status](https://travis-ci.org/mixerapi/bake.svg?branch=master)](https://travis-ci.org/mixerapi/bake)
[![Coverage Status](https://coveralls.io/repos/github/mixerapi/bake/badge.svg?branch=master)](https://coveralls.io/github/mixerapi/bake?branch=master)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE.txt)
[![MixerApi](https://img.shields.io/badge/mixer-api-red?logo=data:image/png;base64,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)](http://mixerapi.com)
[![CakePHP](https://img.shields.io/badge/cakephp-%3E%3D%204.0-red?logo=cakephp)](https://book.cakephp.org/4/en/index.html)
[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.2-8892BF.svg?logo=php)](https://php.net/)
<!--- [![Build Status]()]() [![Coverage Status]()]() --->

Bake RESTful CakePHP controllers in seconds with this API focused bake template.

## Installation 

```bash
composer require mixerapi/bake
bin/cake plugin load MixerApi/Bake
```

Alternatively after composer installing you can manually load the plugin in your Application:

```php
# src/Application.php
public function bootstrap(): void
{
    // other logic...
    $this->addPlugin('MixerApi/Bake');
}
```

## Usage

Add `--theme MixerApi/Bake` to your bake commands.

Examples:
 
```bash
# bake all your controllers
bin/cake bake controller all --theme MixerApi/Bake

# bake a single controller
bin/cake bake controller {ControllerName} --theme MixerApi/Bake

# you can even bake the entire application still, MixerApi/Bake only deals with controller files
bin/cake bake all --everything --theme MixerApi/Bake
```

<details>
  <summary>View sample controller</summary>
    ```php
    <?php
    declare(strict_types=1);
    
    namespace MixerApi\Bake\Test\App\Controller;
    
    
    /**
     * Departments Controller
     *
     * @property \MixerApi\Bake\Test\App\Model\Table\DepartmentsTable $Departments
     * @method \MixerApi\Bake\Test\App\Model\Entity\Department[]|\Cake\Datasource\ResultSetInterface paginate($object = null, array $settings = [])
     */
    class DepartmentsController extends AppController
    {
        /**
         * Index method
         *
         * @return \Cake\Http\Response|null|void Renders view
         * @throws \Cake\Datasource\Exception\MethodNotAllowedException When invalid method
         */
        public function index()
        {
            $this->request->allowMethod('get');
            $departments = $this->paginate($this->Departments);
    
            $this->set(compact('departments'));
            $this->viewBuilder()->setOption('serialize', 'departments');
        }
    
        /**
         * View method
         *
         * @param string|null $id Department id.
         * @return \Cake\Http\Response|null|void Renders view
         * @throws \Cake\Datasource\Exception\RecordNotFoundException When record not found.
         * @throws \Cake\Datasource\Exception\MethodNotAllowedException When invalid method
         */
        public function view($id = null)
        {
            $this->request->allowMethod('get');
    
            $department = $this->Departments->get($id, [
                'contain' => ['DepartmentEmployees'],
            ]);
    
            $this->set('department', $department);
            $this->viewBuilder()->setOption('serialize', 'department');
        }
    
        /**
         * Add method
         *
         * @return \Cake\Http\Response|null|void HTTP 200 on successful add
         * @throws \Cake\Datasource\Exception\MethodNotAllowedException When invalid method
         * @throws \Exception
         */
        public function add()
        {
            $this->request->allowMethod('post');
            $department = $this->Departments->newEmptyEntity();
            $department = $this->Departments->patchEntity($department, $this->request->getData());
            if ($this->Departments->save($department)) {
                $this->set('department', $department);
                $this->viewBuilder()->setOption('serialize', 'department');
    
                return;
            }
            throw new \Exception("Record not created");
        }
    
        /**
         * Edit method
         *
         * @param string|null $id Department id.
         * @return \Cake\Http\Response|null|void HTTP 200 on successful edit
         * @throws \Cake\Datasource\Exception\RecordNotFoundException When record not found.
         * @throws \Cake\Datasource\Exception\MethodNotAllowedException When invalid method
         * @throws \Exception
         */
        public function edit($id = null)
        {
            $this->request->allowMethod(['patch', 'post', 'put']);
            $department = $this->Departments->get($id, [
                'contain' => [],
            ]);
            $department = $this->Departments->patchEntity($department, $this->request->getData());
            if ($this->Departments->save($department)) {
                $this->set('department', $department);
                $this->viewBuilder()->setOption('serialize', 'department');
    
                return;
            }
            throw new \Exception("Record not saved");
        }
    
        /**
         * Delete method
         *
         * @param string|null $id Department id.
         * @return \Cake\Http\Response|null|void HTTP 204 on success
         * @throws \Cake\Datasource\Exception\RecordNotFoundException When record not found.
         * @throws \Cake\Datasource\Exception\MethodNotAllowedException When invalid method
         * @throws \Exception
         */
        public function delete($id = null)
        {
            $this->request->allowMethod(['delete']);
            $department = $this->Departments->get($id);
            if ($this->Departments->delete($department)) {
                return $this->response->withStatus(204);
            }
            throw new \Exception("Record not deleted");
        }
    }
    ```
</details>

## Unit Tests

```bash
vendor/bin/phpunit
```

## Code Standards

```bash
composer check
```
