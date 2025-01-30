# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '0549c7127c2fbab2904892c9d6ff491fa1e93751',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '5165b6d2bdff5244e8aef6408441a962424cf2d1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'e7294a8ebed84f8c5bd3686c68dbe12a4e65b644',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '96b46d160a969c2762f605fb488de57770a63c6c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '39f924b810e561fd86b2558b6711ca68d4363f68',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0508dee4ff864f5034ae6b7f68d34cb2822b827d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7658238ddc50d7ef1fe923d95b7112597a5adc68',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '1ddbe6c40aeaf98d4138f07c325ebb01beeece68',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'cad760ff236cde4ce98916121a7d3118005d6523',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
